
# Learn Intermediate CSS by Building a Picasso Painting, Completed

> - In this course, you'll learn how to use some intermediate CSS techniques by coding your own Picasso painting webpage. You'll learn about SVG icons, CSS positioning, and review other CSS skills you've learned.
---

> **Step 1** <br>


```html
#index.html
<!DOCTYPE html>
<html lang="en">
  <head></head>
  <body></body>
</html>
```
> **Step 2** <br>


```html
#index.html
    <meta charset="UTF-8">
    <title>Picasso Painting</title>
```
> **Step 3** <br>


```html
#index.html
    <link rel="stylesheet" href="./styles.css">
```
> **Step 4** <br>


```html
#index.html
    <link rel ="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css">
```
> **Step 5** <br>


```css
#styles.css
body {
  background-color: rgb(184, 132, 46);
}
```
> **Step 6** <br>


```html
#index.html
    <div id="back-wall"></div>
```
> **Step 7** <br>


```css
#styles.css
#back-wall {
  background-color: #8B4513;
}
```
> **Step 8** <br>


```css
#styles.css
#back-wall {
  background-color: #8B4513;
  width: 100%;
  height: 60%;
}
```
> **Step 9** <br>


```css
#styles.css
#back-wall {
  background-color: #8B4513;
  width: 100%;
  height: 60%;
  position: absolute;
  top: 0;
  left: 0;
}
```
> **Step 10** <br>



#back-wall {
  background-color: #8B4513;
  width: 100%;
  height: 60%;
  position: absolute;
  top: 0;
  left: 0;
  z-index: -1;
}
```
> **Step 11** <br>


```html
#index.html
    <div class="characters"></div>
```
> **Step 12** <br>


```html
#index.html
    <div class="characters">
      <div id="offwhite-character"></div>
    </div>
```
> **Step 13** <br>


```html
#index.html
      <div id="offwhite-character">
        <div id="white-hat"></div>
        <div id="black-mask"></div>
        <div id="gray-instrument"></div>
        <div id="tan-table"></div>
      </div>
```
> **Step 14** <br>


```html
#index.html
        <div id="black-mask">
            <div class="eyes left"></div>
            <div class="eyes right"></div>
        </div>
```
> **Step 15** <br>


```html
#index.html
        <div id="gray-instrument">
            <div class="black-dot"></div>
            <div class="black-dot"></div>
            <div class="black-dot"></div>
            <div class="black-dot"></div>
            <div class="black-dot"></div>
        </div>
```
> **Step 16** <br>


```css
#styles.css
#offwhite-character {
  width: 300px;
  height: 550px;
  background-color: GhostWhite;
}
```
> **Step 17** <br>


```css
#styles.css
#offwhite-character {
  width: 300px;
  height: 550px;
  background-color: GhostWhite;
  position: absolute;
  top: 20%;
  left: 17.5%;
}
```
> **Step 18** <br>


```css
#styles.css
#white-hat {
  width: 0;
  height: 0;
  border-style: solid;
}
```
> **Step 19** <br>


```css
#styles.css
#white-hat {
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 0 120px 140px 180px;
}
```
> **Step 20** <br>


```css
#styles.css
#white-hat {
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 0 120px 140px 180px;
  border-top-color: transparent;
  border-right-color: transparent;
  border-left-color: transparent;
  border-bottom-color: GhostWhite;
}
```
> **Step 21** <br>


```css
#styles.css
#white-hat {
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 0 120px 140px 180px;
  border-top-color: transparent;
  border-right-color: transparent;
  border-left-color: transparent;
  border-bottom-color: GhostWhite;
  position: absolute;
  top: -140px;
  left: 0; 
}
```
> **Step 22** <br>


```css
#styles.css
#black-mask {
  width: 100%;
  height: 50px;
  background-color: rgb(45, 31, 19);
}
```
> **Step 23** <br>


```css
#styles.css
#black-mask {
  width: 100%;
  height: 50px;
  background-color: rgb(45, 31, 19);
  position: absolute;
  top: 0;
  left: 0;
}
```
> **Step 24** <br>


```css
#styles.css
#black-mask {
  width: 100%;
  height: 50px;
  background-color: rgb(45, 31, 19);
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1;
}
```
> **Step 25** <br>


```css
#styles.css
#gray-instrument {
  width: 15%;
  height: 40%;
  background-color: rgb(167, 162, 117);
}
```
> **Step 26** <br>


```css
#styles.css
#gray-instrument {
  width: 15%;
  height: 40%;
  background-color: rgb(167, 162, 117);
  position: absolute;
  top: 50px;
  left: 125px;
}
```
> **Step 27** <br>


```css
#styles.css
#gray-instrument {
  width: 15%;
  height: 40%;
  background-color: rgb(167, 162, 117);
  position: absolute;
  top: 50px;
  left: 125px;
  z-index: 1;
}
```
> **Step 28** <br>


```css
#styles.css
.black-dot {
  width: 10px;
  height: 10px;
  background-color: rgb(45, 31, 19);
}
```
> **Step 29** <br>


```css
#styles.css
.black-dot {
  width: 10px;
  height: 10px;
  background-color: rgb(45, 31, 19);
  border-radius: 50%;
}
```
> **Step 30** <br>


```css
#styles.css
.black-dot {
  width: 10px;
  height: 10px;
  background-color: rgb(45, 31, 19);
  border-radius: 50%;
  display: block;
  margin: auto;
  margin-top: 65%;
}
```
> **Step 31** <br>


```css
#styles.css
#tan-table {
  width:450px;
  height: 140px;
  background-color: #D2691E;
}
```
> **Step 32** <br>


```css
#styles.css
#tan-table {
  width:450px;
  height: 140px;
  background-color: #D2691E;
  position: absolute;
  top: 275px;
  left: 15px;
}
```
> **Step 33** <br>


```css
#styles.css
#tan-table {
  width:450px;
  height: 140px;
  background-color: #D2691E;
  position: absolute;
  top: 275px;
  left: 15px;
  z-index: 1;
}
```
> **Step 34** <br>


```html
#index.html
      <div id="black-character">
```
> **Step 35** <br>


```html
#index.html
        <div id="black-hat"></div>
        <div id="gray-mask"></div>
        <div id="white-paper"></div>
```
> **Step 36** <br>


```html
#index.html
          <div class="eyes left"></div>
          <div class="eyes right"></div>
```
> **Step 37** <br>


```html
#index.html
        <div id="white-paper">
          <i class="fas fa-music"></i>
          <i class="fas fa-music"></i>
          <i class="fas fa-music"></i>
          <i class="fas fa-music"></i>
        </div>
```
> **Step 38** <br>


```css
#styles.css
#black-character {
  width: 300px;
  height: 500px;
  background-color: rgb(45, 31, 19);
}
```
> **Step 39** <br>


```css
#styles.css
#black-character {
  width: 300px;
  height: 500px;
  background-color: rgb(45, 31, 19);
  position: absolute;
  top: 30%;
  left: 59%;
}
```
> **Step 40** <br>


```css
#styles.css
#black-hat {
  width: 0;
  height: 0;
  border-style: solid;
}
```
> **Step 41** <br>


```css
#styles.css
#black-hat {
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 150px 0 0 300px;
}
```
> **Step 42** <br>


```css
#styles.css
#black-hat {
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 150px 0 0 300px;
  border-top-color: transparent;
  border-right-color:transparent;
  border-bottom-color: transparent;
  border-left-color: rgb(45, 31, 19);
}
```
> **Step 43** <br>


```css
#styles.css
#black-hat {
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 150px 0 0 300px;
  border-top-color: transparent;
  border-right-color:transparent;
  border-bottom-color: transparent;
  border-left-color: rgb(45, 31, 19);
  position: absolute;
  top: -150px;
  left: 0;
}
```
> **Step 44** <br>


```css
#styles.css
#gray-mask {
  width: 150px;
  height: 150px;
  background-color: rgb(167, 162, 117);

}
```
> **Step 45** <br>


```css
#styles.css
#gray-mask {
  width: 150px;
  height: 150px;
  background-color: rgb(167, 162, 117);
  position: absolute;
  top: -10px;
  left: 70px;
}
```
> **Step 46** <br>


```css
#styles.css
#white-paper {
  width: 400px;
  height: 100px;
  background-color: GhostWhite;
}
```
> **Step 47** <br>


```css
#styles.css
#white-paper {
  width: 400px;
  height: 100px;
  background-color: GhostWhite;
  position: absolute;
  top: 250px;
  left: -150px;
}
```
> **Step 48** <br>


```css
#styles.css
#white-paper {
  width: 400px;
  height: 100px;
  background-color: GhostWhite;
  position: absolute;
  top: 250px;
  left: -150px;
  z-index: 1; 
}
```
> **Step 49** <br>


```css
#styles.css
.fa-music {
  display: inline-block;
  margin-top: 8%;
  margin-left: 13%;
}
```
> **Step 50** <br>


```css
#styles.css
      <div class="blue" id="blue-left"></div>
      <div class="blue" id="blue-right"></div>
```
> **Step 51** <br>


```css
#styles.css
.blue {
  background-color: #1E90FF;
}
```
> **Step 52** <br>


```css
#styles.css
#blue-left {
  width: 500px;
  height:300px;
}
```
> **Step 53** <br>


```css
#styles.css
#blue-left {
  width: 500px;
  height:300px;
  position: absolute;
  top: 20%;
  left: 20%;
}
```
> **Step 54** <br>


```css
#styles.css
#blue-right {
  width: 400px;
  height: 300px;
}
```
> **Step 55** <br>


```css
#styles.css
#blue-right {
  width: 400px;
  height: 300px;
  position: absolute;
  top: 50%;
  left: 40%;
}
```
> **Step 56** <br>


```css
#styles.css
      <div id="orange-character"></div>
```
> **Step 57** <br>


```css
        <div id="black-round-hat"></div>
        <div id="eyes-div">
        <div id="triangles"></div>
        <div id="guitar"></div>
```
> **Step 58** <br>


```css
#styles.css
          <div class="eyes left"></div>
          <div class="eyes right"></div>
```
> **Step 59** <br>


```css
#styles.css
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
          <div class="triangle"></div>
```
> **Step 60** <br>


```css
#styles.css
          <div class="guitar" id="guitar-left"></div>
          <div class="guitar" id="guitar-right"></div>
          <div id="guitar-neck"></div>
```
> **Step 61** <br>


```css
#styles.css
          <div class="guitar" id="guitar-left">
            <i class="fas fa-bars"></i>
          </div>
          <div class="guitar" id="guitar-right">
            <i class="fas fa-bars"></i>
          </div>
```
> **Step 62** <br>


```css
#styles.css
#orange-character  {
  width:250px;
  height: 550px;
  background-color: rgb(240, 78, 42);
}
```
> **Step 63** <br>


```css
#styles.css
#orange-character {
  width: 250px;
  height: 550px;
  background-color: rgb(240, 78, 42);
  position: absolute;
  top: 25%;
  left: 40%;
}
```
> **Step 64** <br>


```css
#styles.css
#black-round-hat {
  width: 180px;
  height: 150px;
  background-color: rgb(45, 31, 19);
}
```
> **Step 65** <br>


```css
#styles.css
#black-round-hat {
  width: 180px;
  height: 150px;
  background-color: rgb(45, 31, 19);
  border-radius: 50%;
}
```
> **Step 66** <br>


```css
#styles.css
#black-round-hat {
  width: 180px;
  height: 150px;
  background-color: rgb(45, 31, 19);
  border-radius: 50%;
  position: absolute;
  top: -100px;
  left: 5px;
}
```
> **Step 67** <br>


```css
#styles.css
#black-round-hat {
  width: 180px;
  height: 150px;
  background-color: rgb(45, 31, 19);
  border-radius: 50%;
  position: absolute;
  top: -100px;
  left: 5px;
  z-index: -1;
}
```
> **Step 68** <br>


```css
#styles.css
#eyes-div {
  width: 180px;
  height: 50px;
}
```
> **Step 69** <br>


```css
#styles.css
#eyes-div {
  width: 180px;
  height: 50px;
  position: absolute;
  top: -40px;
  left: 20px;
}
```
> **Step 70** <br>


```css
#styles.css
#eyes-div {
  width: 180px;
  height: 50px;
  position: absolute;
  top: -40px;
  left: 20px;
  z-index: 3;
}
```
> **Step 71** <br>


```css
#styles.css
#triangles {
  width: 250px;
  height: 550px;
}
```
> **Step 72** <br>


```css
#styles.css
.triangle {
  width: 0;
  height: 0;
}
```
> **Step 73** <br>


```css
#styles.css
.triangle {
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 42px 45px 45px 0;
}
```
> **Step 74** <br>


```css
#styles.css
.triangle {
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 42px 45px 45px 0;
  border-top-color: transparent;
  border-right-color: Gold;
  border-bottom-color: transparent;
  border-left-color: transparent;
}
```
> **Step 75** <br>


```css
#styles.css
.triangle {
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 42px 45px 45px 0;
  border-top-color: transparent;
  border-right-color: Gold;
  border-bottom-color: transparent;
  border-left-color: transparent;
  display: inline-block;
}
```
> **Step 76** <br>


```css
#styles.css
#guitar {
  width: 100%;
  height: 100px;
}
```
> **Step 77** <br>


```css
#styles.css
#guitar {
  width: 100%;
  height: 100px;
  position: absolute;
  top: 120px;
  left: 0px;
}
```
> **Step 78** <br>


```css
#styles.css
#guitar {
  width: 100%;
  height: 100px;
  position: absolute;
  top: 120px;
  left: 0px;
  z-index: 3;
}
```
> **Step 79** <br>


```css
#styles.css
.guitar {
  width: 150px;
  height: 120px;
  background-color: Goldenrod;
  border-radius: 50%;
}
```
> **Step 80** <br>


```css
#styles.css
#guitar-left {
  position: absolute;
  left: 0px;
}
```

> **Step 81** <br>


```css
#styles.css
#guitar-right {
  position: absolute;
  left: 100px;
}
```
> **Step 82** <br>


```css
#styles.css
.fa-bars {
  display: block;
  margin-top: 30%;
  margin-left: 40%;
}
```
> **Step 83** <br>


```css
#styles.css
#guitar-neck {
  width: 200px;
  height: 30px;
  background-color: #D2691E;
}
```
> **Step 84** <br>


```css
#styles.css
#guitar-neck {
  width: 200px;
  height: 30px;
  background-color: #D2691E;
  position: absolute;
  top: 45px;
  left: 200px;
}
```
> **Step 85** <br>


```css
#styles.css
#guitar-neck {
  width: 200px;
  height: 30px;
  background-color: #D2691E;
  position: absolute;
  top: 45px;
  left: 200px;
  z-index: 3;
}
```
> **Step 86** <br>


```css
#styles.css
.eyes {
  width: 35px;
  height: 20px;
  background-color: #8B4513;
  border-radius: 20px 50%;
}
```
> **Step 87** <br>


```css
#styles.css
.right {
  position: absolute;
  top: 15px;
  right: 30px;
}
```

> **Step 88** <br>


```css
#styles.css
.left {
  position: absolute;
  top: 15px;
  left: 30px;
}
```
> **Step 89** <br>


```css
#styles.css
.fas {
  font-size: 30px;
}
```