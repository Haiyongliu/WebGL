# THREE.js

## Contents

1. WebGL
2. How to run this project.
3. Demos

## 1. WebGL

This is demo for THREE.js

## 2. How to run this demo in ubuntu

- install npm package

- ```npm install http-server```
   ,根目录下是否有package.json文件，没有则添加该文件，编辑写入

   ```{
      "scripts": {
         "start": "http-server -a 0.0.0.0 -p 8000"
      }
   }```

   - ```npm start```
   - 打开浏览器，输入提示网址，例如 http://127.0.0.1:8000/index.html

## 3. 目录

- Basic
    1. Basic_Module.html

       模板
    2. Basic_Scene.html

       最基本几何图形呈现过程。
    3. Basic_line.html

       基础的画线功能。
    4. Basic_BoxBufferGeometry.html

       BoxBuffer几何图形
    5. Basic_BufferLine.html

       Example for showing dynamic lines with vertexs.
    6. AudioPlayer.html

       Example for play audio and positional audio.
    7. Basic_TextureLoader.html

       Example for load jpeg and jpg picture as cubic model.
