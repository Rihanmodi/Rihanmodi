<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<style>

    @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  width: 100%;
  height: 100vh;
  background: #001122;
  display: grid;
  place-items: center;
  font-family: "Poppins", sans-serif;
  font-size: 5rem;
  font-weight: 800;
}
.loader {
  perspective: 1000px;
  -webkit-perspective: 1000px;
}
.loader > span {
  display: inline-block;
  color: #fff;
  transform-style: preserve-3d;
  transform-origin: 0 100%;
  animation: anim 3s infinite linear;
}
.loader > span:nth-child(even) {
  color: #00ed64;
}
.loader > span:nth-child(2) {
  animation-delay: 0.2s;
}
.loader > span:nth-child(3) {
  animation-delay: 0.4s;
}
.loader > span:nth-child(4) {
  animation-delay: 0.6s;
}
.loader > span:nth-child(5) {
  animation-delay: 0.8s;
}
.loader > span:nth-child(6) {
  animation-delay: 1s;
}
.loader > span:nth-child(7) {
  animation-delay: 1.2s;
}
.loader > span:nth-child(8) {
  animation-delay: 1.4s;
}
.loader > span:nth-child(9) {
  animation-delay: 1.6s;
}
.loader > span:nth-child(10) {
  animation-delay: 1.8s;
}
.loader > span:nth-child(11) {
  animation-delay: 2s;
}
.loader > span:nth-child(12) {
  animation-delay: 2.2s;
}
.loader > span:nth-child(13) {
  animation-delay: 2.4s;
}
.loader > span:nth-child(14) {
  animation-delay: 2.6s;
}
@keyframes anim {
  35% {
    transform: rotateX(360deg);
  }
  100% {
    transform: rotateX(360deg);
  }
}


</style>

<body>
    <div class="loader">
        <span>R</span>
        <span>a</span>
        <span>h</span>
        <span>u</span>
        <span>l</span>
        <span>_</span>
        <span>C</span>
        <span>h</span>
        <span>a</span>
        <span>u</span>
        <span>a</span>
        <span>s</span>
        <span>i</span>
        <span>y</span>
        <span>a</span>
      </div>
</body>
</html>
