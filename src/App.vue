<script>
export default {
  data() {
    return {
      bt:' Example- Cat Foods',
      heading: 'Contact For Services +8801741930058.',
      cart: 0,
      display: '',
      bg:'',
      text:'"Pets are such agreeable friends- they ask no questions; they pass no criticisms."',
      bgi:'',
      banner: '',
      h1: 'Welcome to Vet & Pet Master',
      btn:'',
      btn1: 'Login',
      btn2: 'Sign up',
      h4: '',
      p: 'New to Vet & Pet Master?',
      p1: 'Create an accunt.',
      banner1:'',
      list:'',
      fit:'©All Copyright issues is preserved by Vet & Pet Master technical team.'
    }
  }
}
</script>

<template>
  <div class="heading">
  <button type="text" placeholder="Search.." name="search" class="bt"><i>{{ bt }}</i></button>
  <svg class=" src" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" className="w-6 h-6">
  <path strokeLinecap="round" strokeLinejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
</svg>

    <svg class="svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="blue" className="w-6 h-6">
      <path fillRule="evenodd" d="M1.5 4.5a3 3 0 013-3h1.372c.86 0 1.61.586 1.819 1.42l1.105 4.423a1.875 1.875 0 01-.694 1.955l-1.293.97c-.135.101-.164.249-.126.352a11.285 11.285 0 006.697 6.697c.103.038.25.009.352-.126l.97-1.293a1.875 1.875 0 011.955-.694l4.423 1.105c.834.209 1.42.959 1.42 1.82V19.5a3 3 0 01-3 3h-2.25C8.552 22.5 1.5 15.448 1.5 6.75V4.5z" clipRule="evenodd" /></svg>
               {{ heading }} 
        <svg class="sc" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" className="w-6 h-6">
          <path strokeLinecap="round" strokeLinejoin="round" d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 00-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 00-16.536-1.84M7.5 14.25L5.106 5.272M6 20.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm12.75 0a.75.75 0 11-1.5 0 .75.75 0 011.5 0z" /></svg>
          <div class="cart">{{ cart }}</div></div>
              <div class="display">
              <div>Vet & Pet Master</div>
                <div>Home</div>
                 <div>Services</div>
                  <div>Doctors</div>
                   <div>Blog</div>
                    <div>Shopping</div>
                     <div>Peyment</div>
                      <div>About Us</div>
                       <div>Profile</div>
                        {{ display }}
                       </div>  
                       <div class="text">
                       <div class="bg">{{ bg }}</div> 
                       <div class="text1"><i>{{ text }}</i></div>
                       </div>
                       <div class="bgi">{{bgi}}</div>     
                         <div class="banner">
                       <h1 class="h1">{{ h1 }}</h1>
                     <div class="btn"> {{ btn }}
                    <button class="btn1">{{ btn1 }}</button>
                   <button class="btn2">{{ btn2 }}</button> 
                 </div>
              <div class="h4"> {{ h4 }}
            <h4 class="p">{{ p }} </h4>
          <h4 class="p1">{{ p1 }} </h4>
       </div>
    {{ banner }}
</div> 
<div class="banner1">
        <ul class="list">{{ list }} <u>Our Services</u>
            <li><i>Telemedicine</i></li>
            <li><i>E-prescription</i></li>
            <li><i>Online Cosultency</i></li>
            <li><i>Puppy Training</i></li>
            <li><i>Deworming</i></li>
            <li><i>Gromming</i></li>
        </ul>
        <ul class="list">{{ list }} <u>Doctors</u> 
            <li><i>Pet Practitioner</i></li>
            <li><i>Veterinary Surgeon</i></li>
            <li><i>Poultry Practitioner</i></li>
        </ul>
        <ul class="list">{{ list }} <u>Blog</u> 
            <li><i>Pet Animals</i></li>
            <li><i>Ruminants</i></li>
            <li><i>Poultry</i></li>
        </ul>
        <ul class="list">{{ list }} <u>Shopping</u> 
            <li><i>Cat Foods</i></li>
            <li><i>Dog Foots</i></li>
            <li><i>Pet Medicine</i></li>
            <li><i>Pet Toys</i></li>
        </ul>
        <ul class="list">{{ list }} <u>Online Payment</u> 
            <li><i>Peypal</i></li>
            <li><i>Payoneer</i></li>
            <li><i>Bkash</i></li>
            <li><i>Rocket</i></li>
            <li><i>Nagad</i></li>
            <li><i>Upay</i></li>
        </ul>
        <ul class="list">{{ list }} <u>About Us</u> 
            <li><i>Hospitals</i></li>
            <li><i>Location</i></li>
            <li><i>Team</i></li>
            <li><i>FAQs</i></li>
        </ul>
        <ul class="list">{{ list }} <u>Social Media</u> 
            <li><i>Facebook</i></li>
            <li><i>Twitter</i></li>
            <li><i>Linkedin</i></li>
            <li><i>Instagram</i></li>
        </ul>
    {{ banner1}}
    </div>
       <i class="fti">{{ fit }}</i>
</template>

<style>
.heading {
    display: flex;
    background-color: #ADFF2F;
    height: 80px;
    width: auto;
    font-size: large;
    font-family: sans-serif;
    color: blue;
    padding-left: 800px;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}
.bt{
    display: flex;
    position: absolute;
    height: 40px;
    margin-right: 1450px;
    padding: 10px;
    color: grey;
    font-size: 15px;
    border: 2px solid blue;
    float: left;
    width: 35%;
    background: ash;
    cursor: pointer;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}
.src{
    display: flex;
    position: absolute;
    height: 30px;
    margin-right: 1010px;
    cursor: pointer;
    color: blue;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}
.svg{
    display: flex;
    height: 30px;
    cursor: pointer;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}
.sc{
    display: flex;
    height: 50px;
    font: bolder;
    color: blue;
    cursor: pointer;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}
.cart{
  display: flex;
  position: relative;
  top: -16px;
  right: 27px;
  height:15px;
  weight:15px;
  color: blue;
  font: bold;
  cursor: pointer;
  border-radius:50%;
  flex-diraction: column;
  align-items: flex-end;
}
.display{
    display: flex;
    background-color: #00FA9A;
    height: 45px;
    margin-top: -5px;
    padding-left: 5px;
    padding-right: 5px;
    font-size: large;
    cursor: pointer;
    font-family: Georgia, 'Times New Roman', Times, serif;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
}
.bg{
}
.text{
  display: flex;
  height: 490px;
  width:1285;
  background-color: #00ff00;
  margin-bottom: 205px ;
  background-image: url('@/assets/images/vetpetbg.jpg');
  background-repeat: no-repeat;
  align-items: center;
  flex-direction: row;
  justify-content: space-betweeen;
}
.text1{
  display: flex;
  font-size: 30px;
  padding-left: 765px;
  font-family: Georgia, 'Times New Roman', Times, serif;
  color: blue;
}
.bgi{
  display: flex;
  background-image: url('@/assets/images/dogcat.jpg');
  background-repeat:no-repeat;
  margin-top:-206px;
  height:750px;
  width: auto;
  }
.banner{
    display: flex;
    height: 100vh;
    width: auto;
    background-color: ash;
    background-repeat: repeat-y;
    margin-top: -755px;
    padding-right: 65px;
    flex-direction: column;
    align-items: flex-end;
    justify-content: center;
}
.btn{
    display: flex;
    align-items: center;
    flex-direction: row;
    justify-content: space-between;
}
.btn1{
    background-color: paleturquoise;
    border-radius: 10px;
    font-size: medium;
    font-family: Georgia, 'Times New Roman', Times, serif ;
    margin-right: 90px;
    height: 25px;
    width: 90px;
    display: inline-block;
    cursor: pointer;
    display: flex;
    align-items: center;
    flex-direction: row;
    justify-content: center;
}
.btn2{
    background-color: paleturquoise;
    border-radius: 10px;
    font-size: medium;
    font-family: Georgia, 'Times New Roman', Times, serif ;
    margin-right: 90px;
    height: 25px;
    width: 90px;
    display: inline-block;
    cursor: pointer;
    display: flex;
    align-items: center;
    flex-direction: row;
    justify-content: center;
}
.h4{
    display: flex;
    position: relative;
    flex-direction: row;
    align-items:flex-end;
    justify-content: center;
    padding-right: -10px;
}
.p{
    font-size: large;
    font: bold;
    font-family: Georgia, 'Times New Roman', Times, serif ;
}
.p1{
    font-size: large ;
    font: bold;
    color:#3b5998;
    display: inline-block;
    cursor: pointer;
    font-family: Georgia, 'Times New Roman', Times, serif ;
}
.banner1{
    display: flex;
    background-color: navy;
    color: white;
    height: 40vh;
    cursor: pointer;
    margin-top: -55px;
    padding-right: 50px;
    padding-left: 5px;
    font-size: small;
    font-family: sans-serif ;
    flex-direction: row;
    align-items: flex-start;
    justify-content: space-between;
}
.list{
    list-style: none;
}
.fti{
    display: flex;
    background-color: #00ff00;
    border: none;
    height: 12vh;
    width: 100%;
    font: bolder;
    font-size: larger;
    color: blue;
    cursor: pointer;
    align-items: flex-end;
    flex-direction: column;
    justify-content: center;
}
</style>