# Toaster

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <div class="mycanvas">
      <div class="toaster">
        <div class="cover" >
          <div class="b1"></div>
          <div class="b2"></div>
          <div class="b3"></div>
          <div class="shine"></div>
        </div>
        <div class="slot1"></div>
        <div class="slot2">
          <div class="handle1">
            <div class="handle2"></div>
            <div class="handle3"></div>
          </div>
        </div>
        <div class="base2"></div>
        <div class="base1"></div>
        <div class="l1"></div>
        <div class="l2"></div>
        <div class="l3"></div>
        <div class="l4"></div>
        <div class="toastl1">
          <div class="toastl2"></div>
          <div class="toastu1"></div>
          <div class="toastu2"></div>
        </div>
        <div class="toastl3">
          <div class="toastl4"></div>
          <div class="toastu3"></div>
          <div class="toastu4"></div>
        </div>
      </div> 
    </div>
    <header><h2>The Toast is Almost Ready...<h2></header>
  </body>
</html>
    
body {
  background-color: #ffe066;
  margin:0;
  padding: 0;
}

.mycanvas {
  height: 510px;
  width: 350px;
  margin:auto;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}
.toaster {
  background-color: #5abff2;
  height: 90px;
  width: 120px;
  position: relative;
  top:210px;
  left:125px;
  border-radius: 20px 25px 0 0;
}
.cover {
  background-color: #99ddff;
  height: 90px;
  width: 120px;
  border-radius: 20px 25px 0 0;
  position: relative;
  right: 30px;
}
.b1, .b2 {
  background-color: #737373;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  position: relative;
}
.b1 {
  top: 20px;
  left: 50px;
}
.b2 {
  top: 25px;
  left: 50px;
}
.b3 {
  background-color: #5abff2;
  height: 16px;
  width: 16px;
  position: relative;
  top: 30px;
  left: 46.5px;
  border-radius: 50%;
  border: 2px solid white;
}
.shine {
  position: relative;
  height: 24px;
  width: 15px;
  background-color: #e6f7ff;
  border-radius: 50%;
  transform: rotate(30deg);
  bottom: 35px;
  left:7px;
}
.slot1 {
  position: relative;
  background-color:#666666;
  height: 43px;
  width: 8px;
  border-radius: 15px;
  bottom: 65px;
  left: 101px;
}
.slot2 {
  position: relative;
  background-color: #333333;
  height: 41px;
   width: 5px;
   bottom: 107px;
   left:101px;
   border-radius: 15px;
}
.handle1 {
  background-color: white;
  height: 5px;
  width: 20px;
  position: relative;
  left: 0.1px;
  top: 1.7px;
  animation: 6s move infinite;
}
@keyframes move {
  50% {
    transform: translateY(31px);
  }
}
.handle2 {
  position: relative;
  background-color: #666666;
  height: 10px;
  width: 18px;
  border-radius: 5px;
  left: 7.5px;
  bottom:2px;
}
.handle3 {
  position: relative;
  background-color: #333333;
  height: 9.5px;
  width: 8px;
  border-radius: 50%;
  left: 16.5px;
  bottom: 12px;
}
.base1 {
  background-color: #666666;
  width: 128px;
  height: 10px;
  border-radius: 15px;
  position: relative;
  bottom: 102.1px;
  right: 33px;
}
.base2 {
  background-color: #333333;
  width: 30px;
  height: 10px;
  border-radius: 15px;
  position: relative;
  bottom: 93px;
  left: 90px;
}
.l1, .l2, .l3, .l4 {
  height: 7px;
  width: 8px;
  background-color: #333333;
  position: relative;
}
.l1 {
  bottom: 103px;
  right: 20px;
}
.l2 {
  bottom: 110px;
  left: 10px;
}
.l3 {
  bottom: 117px;
  left: 80px;
}
.l4 {
  bottom: 124px;
  left:105px;
}
.toastl1 {
  background-color: #cc8800;
  width: 59px;
  height: 15px;
  border-radius: 15px;
  position: relative;
  bottom: 255px;
  left:24px;
  z-index: -60;
  animation: 6s toast infinite;
}
@keyframes toast {
  50% {
    transform: translateY(25px);
  }
  80% {
    transform: translateY(-26px);
  }
}
.toastl2 {
  background-color: #cc8800;
  width: 52px;
  height: 45px;
  position: relative;
  top: 5px;
  left: 2.8px;
}
.toastu1 {
  background-color: #ffd480;
  height: 8px;
  width: 51px;
  border-radius: 15px;
  position: relative;
  bottom: 41px;
  left: 3px;
}
.toastu2 {
  background-color: #ffd480;
  width: 42px;
  height: 35px;
  position: relative;
  bottom: 41px;
  left: 7.3px;
}
.toastl3 {
  background-color: #cc8800;
  width: 59px;
  height: 15px;
  border-radius: 15px;
  position: relative;
  bottom: 275px;
  right: 2px;
  z-index: -1;
  animation: 6s toastt infinite;
}
@keyframes toastt{
  50% {
    transform: translateY(27px);
  }
  87% {
    transform: translateY(-30px);
  }
}
.toastl4 {
  background-color: #cc8800;
  width: 52px;
  height: 45px;
  position: relative;
  top: 5px;
  left: 2.8px;
}
.toastu3 {
  background-color: #ffd480;
  height: 8px;
  width: 51px;
  border-radius: 15px;
  position: relative;
  bottom: 41px;
  left: 3px;
}
.toastu4 {
  background-color: #ffd480;
  width: 42px;
  height: 35px;
  position: relative;
  bottom: 41px;
  left: 7.4px;
}
header {
  color: #99ddff;
  text-align: center;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
