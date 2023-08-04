<!-- Header -->
<div id="top" align="center">
  <br />
  
  <!-- Logo -->
  <img src="https://git.zakscode.com/repo-avatars/cfafeecfa694a538cca613976c94203cd48fe506260f6a6b69892545c493b673" alt="Logo" width="200" height="200">

  <!-- Title -->
  ### Animated Cube
  
  <!-- Description -->
  Animated 4x4x4 LED cube

  <!-- Repo badges -->
  [![Pull Requests](https://img.shields.io/badge/dynamic/json.svg?label=Pull%20Requests&style=for-the-badge&url=https://git.zakscode.com/api/v1/repos/ztimson/291st&query=open_pr_counter)](https://git.zakscode.com/ztimson/291st/pulls)

</div>

## Table of Contents
- [Animated Cube](#top)
- [About](#about)
  - [Built With](#built-with)
- [Demo](#demo)
- [License](#license)

## About

<img src="./gallery/picture.jpg" alt="Logo" width="200" height="200">
<img src="./gallery/Multiplex.svg" alt="Logo" width="200" height="200">
<br />
<br />

This repo contains code for running a 4x4x4 (64 total) [multiplexed](https://en.wikipedia.org/wiki/Multiplexing) LED cube.

4 LED's are wired into columns using their annode. 16 columns are then wired together creating the cube, connecting each layer (16 LEDs) together by their cathode. By keeping each layer & column disconnected, individual LED's can be toggled on by connecting the desired column & layer. Multiple LEDs can be turned on at once by individually blinking each LED faster than the eye can see. By rendering multiple "frames" in quick succession patterns can be created on the cube.

Animations are run using an [Arduino Nano](https://store.arduino.cc/products/arduino-nano).

### Built With
[![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)](https://www.arduino.cc/)
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus)](https://cplusplus.com/)

## Demo

Video of what it looks like: https://www.youtube.com/watch?v=4pzxR-ZhbJA

**Disclaimer:** I did not create the video but it is made using the same idea

## License
Copyright © 2023 Zakary Timson | All Rights Reserved

See the [license](./LICENSE) for more information.
