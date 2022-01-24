# (W12) HMS AR Engine Service
12th week content of COOP4423 course

![Latest Version](https://img.shields.io/badge/latestVersion-1.0-yellow) ![Java](https://img.shields.io/badge/language-java-blue) ![Minimum SDK Version](https://img.shields.io/badge/minSDK-21-orange)

## Used Technologies
In this project, I developed a simple AR image application from using Huawei AR Engine. I did my development with Java in Android Studio. I created a folder called rendering and added the classes I use for image rendering.

- BackgroundRenderer: This class background texture is used for background texture rendering. 
- DisplayRotationHelper: This class listens for image changes and makes the necessary adjustments. 
- ShaderHelper: This class is used to shade the object we will draw. 
- VirtualObjectRenderer: This class will take part in the creation of our previously mentioned virtual object. 
- We use our CameraPermissionHelper class for camera permission. 
- MainActivity must implement the GLSurfaceView.Renderer interface. 
- We use shaders for background and object. There are two types of shaders in this project: Vertex Shader and Fragment Shader. 
    - Vertex Shader converts shape positions to 3D drawing coordinates. 
    - Fragment Shader calculates renderings of a shape's colors and other attributes. You can add them to the raw folder in the res folder.

## Clone the Repository

### With SSH
```
git clone git@github.com:BAU-COOP4423/W12-HMS-AR-Engine.git
```

### With HTTPS
```
git clone https://github.com/BAU-COOP4423/W12-HMS-AR-Engine.git
```

## Utilized resources
- <a href="https://developer.huawei.com/consumer/en/codelab/HWAREngine/index.html#0">HMS AR Engine Integration Codelab Steps</a>



#### Note:
> Do not hesitate to open an <a href="https://github.com/BAU-COOP4423/W3-MVVM-Retrofit/issues" target="_blank">issue</a> for your questions.

