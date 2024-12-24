# Ex09 Event Registration Web Application
## Date:24-12-2024

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
'''
Home page 

<div style="width: 440px; height: 956px; position: relative; background: white">
  <img style="width: 2678px; height: 4014px; left: -1745px; top: -2709px; position: absolute" src="https://via.placeholder.com/2678x4014" />
  <img style="width: 372px; height: 87px; left: 34px; top: 81px; position: absolute" src="https://via.placeholder.com/372x87" />
  <div style="left: 213px; top: 742px; position: absolute; color: white; font-size: 12px; font-family: Inter; font-weight: 400; word-wrap: break-word"><br/></div>
  <div style="width: 382px; height: 166px; left: 89px; top: 429px; position: absolute; color: black; font-size: 50px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">Sports day<br/>     Events</div>
  <div style="width: 216px; height: 60px; left: 106px; top: 660px; position: absolute; background: #D9D9D9"></div>
  <div style="left: 166px; top: 673px; position: absolute; color: black; font-size: 36px; font-family: Inter; font-weight: 600; word-wrap: break-word">Login</div>
  <div style="width: 216px; height: 65px; left: 106px; top: 794px; position: absolute; background: #D9D9D9"></div>
  <div style="left: 147px; top: 805px; position: absolute; color: black; font-size: 36px; font-family: Inter; font-weight: 600; word-wrap: break-word">Register</div>
</div>

Events page

<div style="width: 440px; height: 956px; position: relative; background: white">
  <img style="width: 2678px; height: 4014px; left: -2210px; top: -2393px; position: absolute" src="https://via.placeholder.com/2678x4014" />
  <div style="left: 109px; top: 108px; position: absolute; color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">sports day events</div>
  <div style="width: 241px; height: 639px; left: 35px; top: 254px; position: absolute"><span style="color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">CRICKET<br/></span><span style="color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word"><br/><br/></span><span style="color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">BADMINTON<br/></span><span style="color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word"><br/><br/></span><span style="color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">VOLLEYBALL<br/></span><span style="color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word"><br/><br/></span><span style="color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">100 MTS<br/></span><span style="color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word"><br/><br/></span><span style="color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">200 MTS<br/></span><span style="color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word"><br/><br/></span><span style="color: white; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">4=100 RELAY</span></div>
</div>

Events Registration

<div style="width: 440px; height: 956px; position: relative; background: white">
  <img style="width: 2678px; height: 4014px; left: -1228px; top: -1796px; position: absolute" src="https://via.placeholder.com/2678x4014" />
  <div style="left: 41px; top: 34px; position: absolute; color: #F6F0F9; font-size: 25px; font-family: Inter; font-style: italic; font-weight: 800; word-wrap: break-word">EVENT REGISTRATION FORM</div>
  <div style="left: 41px; top: 64px; position: absolute; color: white; font-size: 20px; font-family: Inter; font-weight: 100; word-wrap: break-word">Fill the details</div>
  <div style="width: 300px; height: 35px; left: 41px; top: 110px; position: absolute; background: #D9D9D9"></div>
  <div style="left: 49px; top: 112px; position: absolute; color: black; font-size: 25px; font-family: Inter; font-weight: 100; word-wrap: break-word">Full name</div>
  <div style="width: 225px; height: 40px; left: 43px; top: 171px; position: absolute; background: #D9D9D9"></div>
  <div style="left: 43px; top: 176px; position: absolute; color: black; font-size: 25px; font-family: Inter; font-weight: 100; word-wrap: break-word">Gender</div>
  <div style="width: 222px; height: 37px; left: 46px; top: 234px; position: absolute; background: #D9D9D9"></div>
  <div style="left: 49px; top: 237px; position: absolute; color: black; font-size: 25px; font-family: Inter; font-weight: 100; word-wrap: break-word">Age</div>
  <div style="width: 303px; height: 42px; left: 46px; top: 302px; position: absolute; background: #D9D9D9"></div>
  <div style="left: 49px; top: 314px; position: absolute; color: black; font-size: 25px; font-family: Inter; font-weight: 100; word-wrap: break-word">Registration number</div>
  <div style="width: 263px; height: 36px; left: 46px; top: 367px; position: absolute; background: #D9D9D9"></div>
  <div style="left: 54px; top: 375px; position: absolute; color: black; font-size: 25px; font-family: Inter; font-weight: 100; word-wrap: break-word">Department</div>
  <div style="width: 270px; height: 39px; left: 46px; top: 494px; position: absolute; background: #D9D9D9"></div>
  <div style="width: 267px; height: 49px; left: 49px; top: 578px; position: absolute; background: #D9D9D9"></div>
  <div style="width: 264px; height: 44px; left: 52px; top: 683px; position: absolute; background: #D9D9D9"></div>
  <div style="left: 50px; top: 503px; position: absolute; color: black; font-size: 25px; font-family: Inter; font-weight: 100; word-wrap: break-word">Mobile number</div>
  <div style="left: 52px; top: 588px; position: absolute; color: black; font-size: 25px; font-family: Inter; font-weight: 100; word-wrap: break-word">Email ID</div>
  <div style="left: 57px; top: 690px; position: absolute; color: black; font-size: 25px; font-family: Inter; font-weight: 100; word-wrap: break-word">Events to register</div>
  <div style="width: 186px; height: 58px; left: 163px; top: 765px; position: absolute; background: #CB1A1A"></div>
  <div style="left: 198px; top: 776px; position: absolute; color: black; font-size: 30px; font-family: Inter; font-weight: 600; word-wrap: break-word">Register</div>
</div>

Contact page

<div style="width: 440px; height: 956px; position: relative; background: white">
  <img style="width: 2764px; height: 3546px; left: -1831px; top: 0px; position: absolute" src="https://via.placeholder.com/2764x3546" />
  <img style="width: 295px; height: 67px; left: 72px; top: 36px; position: absolute" src="https://via.placeholder.com/295x67" />
  <div style="left: 113px; top: 237px; position: absolute; color: black; font-size: 35px; font-family: Inter; font-weight: 900; word-wrap: break-word">THANK YOU</div>
  <div style="width: 290px; height: 64px; left: 77px; top: 341px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 900; word-wrap: break-word"> We are all eagerly waiting for your participation in the sports event</div>
  <div style="left: 104px; top: 678px; position: absolute; text-align: center; color: #D9D9D9; font-size: 30px; font-family: Inter; font-weight: 900; word-wrap: break-word">CONTACT US</div>
  <div style="left: 26px; top: 787px; position: absolute; text-align: center; color: white; font-size: 15px; font-family: Inter; font-weight: 900; word-wrap: break-word">Email:saveethaengineeringcollege@gmail.com</div>
  <div style="left: 99px; top: 830px; position: absolute; text-align: center; color: white; font-size: 20px; font-family: Inter; font-weight: 900; word-wrap: break-word"> Phone: 6369183394<br/>6369183394</div>
</div>

'''


## OUTPUT:
![alt text](<Screenshot 2024-12-23 221030.png>) 
![alt text](<Screenshot 2024-12-23 221041.png>) 
![alt text](<Screenshot 2024-12-23 221054.png>) 
![alt text](<Screenshot 2024-12-23 221019.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
