# Ex09 Event Registration Web Application
## Date:
19/12/2024
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
```
Home pages

<div style="width: 100%; height: 100%; position: relative; background: #C61515">
    <img style="width: 221px; height: 411px; left: 555px; top: 301px; position: absolute; transform: rotate(180deg); transform-origin: 0 0" src="https://via.placeholder.com/221x411" />
    <img style="width: 424px; height: 940px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/424x940" />
    <img style="width: 443px; height: 114px; left: -9px; top: 36px; position: absolute" src="https://via.placeholder.com/443x114" />
    <div style="width: 4px; height: 12px; left: 38px; top: 352px; position: absolute; transform: rotate(180deg); transform-origin: 0 0; background: #D9D9D9"></div>
    <div style="width: 183px; height: 12px; left: 86px; top: 352px; position: absolute"><span style="color: #220404; font-size: 12px; font-family: Inter; font-weight: 400; word-wrap: break-word">          </span><span style="color: #220404; font-size: 40px; font-family: Inter; font-weight: 400; word-wrap: break-word">GRAND<br/>     KITE<br/>    EVENT</span></div>
    <div style="width: 302px; height: 72px; left: 73px; top: 595px; position: absolute; background: #180202; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)"></div>
    <div style="width: 299px; height: 68px; left: 76px; top: 599px; position: absolute; text-align: center; color: white; font-size: 48px; font-family: Inter; font-style: italic; font-weight: 500; word-wrap: break-word">REGISTER</div>
</div>

//           
color: #220404;
 font-size: 12px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word
---
// GRAND<br/>     KITE<br/>    EVENT
color: #220404;
 font-size: 40px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word
---
// REGISTER
color: white;
 font-size: 48px;
 font-family: Inter;
 font-style: italic;
 font-weight: 500;
 word-wrap: break-word

page 2

<div style="width: 100%; height: 100%; position: relative; background: white">
    <img style="width: 430px; height: 932px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/430x932" />
    <div style="width: 264px; height: 667px; left: 104px; top: 91px; position: absolute; color: #1B0808; font-size: 36px; font-family: Inter; font-weight: 400; word-wrap: break-word">things to take on.......<br/><br/>*chief guest speech<br/><br/>*kite release<br/><br/>*competition starts<br/><br/>*prize distribution<br/><br/>*thanks giving</div>
</div>

// things to take on.......<br/><br/>*chief guest speech<br/><br/>*kite release<br/><br/>*competition starts<br/><br/>*prize distribution<br/><br/>*thanks giving
color: #1B0808;
 font-size: 36px;
 font-family: Inter;
 font-weight: 400;
 word-wrap: break-word

page 3

<div style="width: 100%; height: 100%; position: relative; background: white">
    <img style="width: 457px; height: 927px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/457x927" />
    <div style="width: 312px; height: 99px; left: 85px; top: 70px; position: absolute; background: #150202"></div>
    <div style="width: 308px; height: 95px; left: 89px; top: 74px; position: absolute; text-align: center; color: white; font-size: 36px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">REGISTRATION FORM</div>
    <div style="width: 283px; height: 53px; left: 97px; top: 251px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 283px; height: 46px; left: 97px; top: 258px; position: absolute; color: black; font-size: 20px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">full name</div>
    <div style="width: 6px; height: 3px; left: 380px; top: 304px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 283px; height: 47px; left: 97px; top: 326px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 279px; height: 25px; left: 101px; top: 339px; position: absolute; color: black; font-size: 20px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">gender</div>
    <div style="width: 283px; height: 46px; left: 97px; top: 395px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 280px; height: 28px; left: 100px; top: 405px; position: absolute; color: black; font-size: 20px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">age</div>
    <div style="width: 283px; height: 42px; left: 97px; top: 463px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 283px; height: 41px; left: 97px; top: 464px; position: absolute; color: black; font-size: 20px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">register no</div>
    <div style="width: 283px; height: 49px; left: 97px; top: 527px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 284px; height: 26px; left: 99px; top: 540px; position: absolute; color: black; font-size: 20px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">mobile no</div>
    <div style="width: 283px; height: 46px; left: 97px; top: 598px; position: absolute; background: #D9D9D9"></div>
    <div style="width: 280px; height: 33px; left: 100px; top: 611px; position: absolute; color: black; font-size: 20px; font-family: Inter; font-style: italic; font-weight: 900; word-wrap: break-word">e-mail</div>
</div>

// REGISTRATION FORM
color: white;
 font-size: 36px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// full name
color: black;
 font-size: 20px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// gender
color: black;
 font-size: 20px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// age
color: black;
 font-size: 20px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// register no
color: black;
 font-size: 20px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// mobile no
color: black;
 font-size: 20px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word
---
// e-mail
color: black;
 font-size: 20px;
 font-family: Inter;
 font-style: italic;
 font-weight: 900;
 word-wrap: break-word

```



## OUTPUT:
![alt text](<Screenshot 2024-12-20 225439.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
