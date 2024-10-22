<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Flower Design</title>
  <style>
    /* Container for the flower */
    .flower {
      position: relative;
      width: 200px;
      height: 200px;
      margin: 50px auto;
    }

    /* Petals of the flower */
    .petal {
      position: absolute;
      width: 60px;
      height: 120px;
      background-color: pink;
      border-radius: 50%;
      top: 20px;
      left: 70px;
      transform-origin: center;
      transform: rotate(0deg);
      animation: rotatePetals 5s infinite linear;
    }

    /* Animating petal rotation */
    @keyframes rotatePetals {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }

    /* Different rotations for each petal */
    .petal:nth-child(1) {
      transform: rotate(0deg) translateX(80px);
    }

    .petal:nth-child(2) {
      transform: rotate(45deg) translateX(80px);
    }

    .petal:nth-child(3) {
      transform: rotate(90deg) translateX(80px);
    }

    .petal:nth-child(4) {
      transform: rotate(135deg) translateX(80px);
    }

    .petal:nth-child(5) {
      transform: rotate(180deg) translateX(80px);
    }

    .petal:nth-child(6) {
      transform: rotate(225deg) translateX(80px);
    }

    .petal:nth-child(7) {
      transform: rotate(270deg) translateX(80px);
    }

    .petal:nth-child(8) {
      transform: rotate(315deg) translateX(80px);
    }

    /* Flower center */
    .center {
      position: absolute;
      width: 60px;
      height: 60px;
      background-color: yellow;
      border-radius: 50%;
      top: 70px;
      left: 70px;
    }
  </style>
</head>
<body>
  <div class="flower">
    <div class="petal"></div


<!---
SaShaaAAA5/SaShaaAAA5 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
