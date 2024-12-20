# Ex09 Event Registration Web Application
## Date:20-12-2024

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:

Homepage
html code:
```
<div class="container--0-">
  <img
    src="data:image/jpeg;base64"
      /><img
    src="data:image/png;base64"
      /><img
    src="data:image/png;base64"
     /><svg
    width="142"
    height="44"
    viewBox="0 0 142 44"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="142" height="44" rx="20" fill="#454340"></rect>
  </svg>
  <div class="text-0-1-4">LOGIN</div>
  <div class="container-0-1-5"></div>
  <div class="text-0-1-6">REGISTER</div>
  <div class="text-0-1-7">co-ordinator - dhanus karthi</div>
</div>
```
css code:
```
.container--0- {
  position: absolute;
  left: -233px;
  top: -368px;
  width: 393px;
  height: 806px;
  background-color: #e2d2d2fc;
  justify-content: start;
  align-items: start;
}
.text-0-1-4 {
  width: 116px;
  height: 44px;
  color: #000000;
  border-width: 1px;
  border-style: solid;
  border-color: #f5f3f3;
  box-shadow: 0px 4px 4px 0 #000000;
  font-size: 36px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.container-0-1-5 {
  position: absolute;
  left: 92px;
  top: 402px;
  width: 206px;
  height: 72px;
  background-color: #454340;
  border-width: 1px;
  border-style: solid;
  border-color: #000000;
  box-shadow: 0px 4px 4px 0 #000000;
  justify-content: start;
  align-items: start;
  border-radius: 20px;
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
  border-bottom-left-radius: 20px;
  border-bottom-right-radius: 20px;
}
.text-0-1-6 {
  width: 181px;
  height: 80px;
  color: #000000;
  border-width: 1px;
  border-style: solid;
  border-color: #f1ecec;
  box-shadow: 0px 4px 4px 0 #000000;
  font-size: 36px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-7 {
  width: 272px;
  height: 25px;
  color: #ffffff;
  font-size: 22px;
  font-family: Inria Sans, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
```

Event pages
Html code:
```
<div class="container--0-">
  <img
    src="data:image/jpeg;base64"
      /><img
    src="data:image/png;base64"
      /><svg
    width="181"
    height="48"
    viewBox="0 0 181 48"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="181" height="48" rx="20" fill="#A09292"></rect></svg
  ><svg
    width="184"
    height="44"
    viewBox="0 0 184 44"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="184" height="44" rx="20" fill="#38DA86"></rect>
  </svg>
  <div class="text-0-1-4">FOOTBALL</div>
  <div class="text-0-1-5">CRICKET</div>
  <svg
    width="184"
    height="45"
    viewBox="0 0 184 45"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="184" height="45" rx="20" fill="#F35151"></rect></svg
  ><svg
    width="187"
    height="44"
    viewBox="0 0 187 44"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="187" height="44" rx="20" fill="#8288FA"></rect></svg
  ><svg
    width="186"
    height="44"
    viewBox="0 0 186 44"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="186" height="44" rx="20" fill="#E1B75E"></rect></svg
  ><svg
    width="221"
    height="90"
    viewBox="0 0 221 90"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_i_7_37)">
      <rect width="221" height="90" rx="40" fill="#121010"></rect>
    </g>
    <defs>
      <filter
        id="filter0_i_7_37"
        x="0"
        y="0"
        width="221"
        height="94"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_7_37"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-10">NEXT</div>
  <div class="text-0-1-11">HOCKEY</div>
  <div class="text-0-1-12">ATHLETICS</div>
  <div class="text-0-1-13">HANDBALL</div>
  <svg
    width="242"
    height="81"
    viewBox="0 0 242 81"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect
      width="242"
      height="81"
      rx="40.5"
      fill="#FF136A"
      fill-opacity="0.99"
    ></rect>
  </svg>
  <div class="text-0-1-15">sports events</div>
  <div class="text-0-1-16"><br />co-ordinator - dhanus karthi</div>
  <div class="container-0-1-17">
    <img
      src="data:image/jpeg;base64"
        /><img
      src="data:image/png;base64"
       /><img
      src="data:image/png;base64"
          />
    <div class="text-1-2-3">co-ordinator - dhanus karthi</div>
    <div class="text-1-2-5">form</div>
    <div class="container-1-2-8">
      <img
        src="data:image/jpeg;base64"
              /><img
        src="data:image/png;base64"
              /><img
        src="data:image/png;base64"
             />
      <div class="text-2-3-4">co-ordinator - dhanus karthi</div>
      <div class="text-2-3-5">THANK YOU FOR REGISTERING</div>
    </div>
    <div class="text-1-2-10">MOBILE NO</div>
    <div class="text-1-2-12">EMAIL ID</div>
    <div class="text-1-2-14">FULL NAME</div>
    <div class="text-1-2-15">REGISTER NO</div>
    <div class="text-1-2-16">GENDER</div>
    <div class="text-1-2-18">EVENT TO REGISTER</div>
  </div>
</div>
```
css code:
```
.container--0- {
  position: absolute;
  left: 361px;
  top: -365px;
  width: 408px;
  height: 799px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-4 {
  width: 181px;
  height: 22px;
  color: #000000;
  font-size: 36px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-5 {
  width: 139px;
  height: 44px;
  color: #000000;
  font-size: 36px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-10 {
  width: 85px;
  height: 44px;
  color: #ffffff;
  font-size: 36px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-11 {
  width: 133px;
  height: 44px;
  color: #000000;
  font-size: 36px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-12 {
  width: 178px;
  height: 44px;
  color: #100f0f;
  font-size: 36px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-13 {
  width: 176px;
  height: 44px;
  color: #000000;
  font-size: 36px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-15 {
  width: 222px;
  height: 44px;
  color: #ffffff;
  border-width: 1px;
  border-style: solid;
  border-color: #8288fa;
  font-size: 36px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-16 {
  width: 270px;
  height: 52px;
  color: #ffffff;
  font-size: 22px;
  font-family: Inria Sans, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.container-0-1-17 {
  position: absolute;
  left: -571px;
  top: 0px;
  width: 394px;
  height: 797px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-1-2-3 {
  width: 270px;
  height: 26px;
  color: #ffffff;
  font-size: 22px;
  font-family: Inria Sans, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-1-2-5 {
  width: 80px;
  height: 77px;
  color: #f5f3f3;
  font-size: 30px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.container-1-2-8 {
  position: absolute;
  left: 582px;
  top: 0px;
  width: 397px;
  height: 797px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-2-3-4 {
  width: 270px;
  height: 41px;
  color: #ffffff;
  font-size: 22px;
  font-family: Inria Sans, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-2-3-5 {
  width: 191.00961303710938px;
  height: 91.00276947021484px;
  color: #0b0909;
  border-width: 1px;
  border-style: solid;
  border-color: #ff0d0d;
  font-size: 25px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-1-2-10 {
  width: 139px;
  height: 52px;
  color: #0b0909;
  font-size: 20px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-1-2-12 {
  width: 112px;
  height: 52px;
  color: #000000;
  font-size: 20px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-1-2-14 {
  width: 158px;
  height: 57px;
  color: #000000;
  font-size: 22px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-1-2-15 {
  width: 165px;
  height: 52px;
  font-size: 20px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-1-2-16 {
  width: 103px;
  height: 52px;
  color: #000000;
  font-size: 20px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-1-2-18 {
  width: 253px;
  height: 52px;
  color: #000000;
  font-size: 20px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
```
Registration page
Html code:
```
<div class="container--0-">
  <div class="container-0-1-0">
    <img
      src="data:image/jpeg;base64"
          /><img
      src="data:image/png;base64"
          /><img
      src="data:image/png;base64"
          />
    <div class="text-1-2-4">co-ordinator - dhanus karthi</div>
    <div class="text-1-2-5">THANK YOU FOR REGISTERING</div>
  </div>
  <img
    src="data:image/jpeg;base64"
      /><img
    src="data:image/png;base64"
      /><img
    src="data:image/png;base64"
      /><svg
    width="90"
    height="35"
    viewBox="0 0 90 35"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="90" height="35" rx="12" fill="#FF0D0D"></rect></svg
  ><svg
    width="302"
    height="43"
    viewBox="0 0 302 43"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="302" height="43" rx="21.5" fill="#66A3AA"></rect></svg
  ><svg
    width="302"
    height="41"
    viewBox="0 0 302 41"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="302" height="41" rx="20.5" fill="#66A3AA"></rect></svg
  ><svg
    width="301"
    height="43"
    viewBox="0 0 301 43"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="301" height="43" rx="21.5" fill="#66A3AA"></rect>
  </svg>
  <div class="text-0-1-8">MOBILE NO</div>
  <svg
    width="302"
    height="41"
    viewBox="0 0 302 41"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="302" height="41" rx="20.5" fill="#66A3AA"></rect>
  </svg>
  <div class="text-0-1-10">EMAIL ID</div>
  <svg
    width="302"
    height="43"
    viewBox="0 0 302 43"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="302" height="43" rx="21.5" fill="#66A3AA"></rect>
  </svg>
  <div class="text-0-1-12">FULL NAME</div>
  <div class="text-0-1-13">REGISTER NO</div>
  <div class="text-0-1-14">GENDER</div>
  <svg
    width="302"
    height="48"
    viewBox="0 0 302 48"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="302" height="48" rx="22" fill="#38DA86"></rect>
  </svg>
  <div class="text-0-1-16">EVENT TO REGISTER</div>
  <div class="text-0-1-17">co-ordinator - dhanus karthi</div>
  <div class="text-0-1-18">form</div>
</div>
```
css code:
```
.container--0- {
  position: absolute;
  left: 970px;
  top: -363px;
  width: 394px;
  height: 797px;
  background-color: #fffafa;
  justify-content: start;
  align-items: start;
}
.container-0-1-0 {
  position: absolute;
  left: 582px;
  top: 0px;
  width: 397px;
  height: 797px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-1-2-4 {
  width: 270px;
  height: 41px;
  color: #ffffff;
  font-size: 22px;
  font-family: Inria Sans, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-1-2-5 {
  width: 191.00961303710938px;
  height: 91.00276947021484px;
  color: #0b0909;
  border-width: 1px;
  border-style: solid;
  border-color: #ff0d0d;
  font-size: 25px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-8 {
  width: 139px;
  height: 53px;
  color: #0b0909;
  font-size: 20px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-10 {
  width: 112px;
  height: 53px;
  color: #000000;
  font-size: 20px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-12 {
  width: 158px;
  height: 58px;
  color: #000000;
  font-size: 22px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-13 {
  width: 165px;
  height: 53px;
  font-size: 20px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-14 {
  width: 103px;
  height: 53px;
  color: #000000;
  font-size: 20px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-16 {
  width: 253px;
  height: 53px;
  color: #000000;
  font-size: 20px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-17 {
  width: 270px;
  height: 26px;
  color: #ffffff;
  font-size: 22px;
  font-family: Inria Sans, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-18 {
  width: 79px;
  height: 57px;
  color: #1c1616;
  border-width: 1px;
  border-style: solid;
  border-color: #a09292;
  box-shadow: 0px 4px 4px 0 #000000;
  font-size: 22px;
  font-family: Inknut Antiqua, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
```
End page
Html code:
```
<div class="container--0-">
  <img
    src="data:image/jpeg;base64"
      /><img
    src="data:image/png;base64"
      /><img
    src="data:image/png;base64"
      /><svg
    width="172"
    height="95"
    viewBox="0 0 172 95"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="172" height="95" rx="25" fill="#FF5E08"></rect>
  </svg>
  <div class="text-0-1-4">Thank you for registering</div>
  <div class="text-0-1-5">Co-ordinator - Dhanus karthi</div>
</div>
```
css code:
```
.container--0- {
  position: absolute;
  left: 1565px;
  top: -363px;
  width: 397px;
  height: 797px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-4 {
  width: 148px;
  height: 54px;
  color: #000000;
  font-size: 22px;
  font-family: Irish Grover, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-5 {
  width: 274px;
  height: 24px;
  color: #ffffff;
  font-size: 22px;
  font-family: Inria Sans, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
```
## OUTPUT:
![alt text](<Screenshot (64).png>)
![alt text](<Screenshot (65).png>)
![alt text](<Screenshot (66).png>)
![alt text](<Screenshot (67).png>)
![alt text](<Screenshot (68).png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
