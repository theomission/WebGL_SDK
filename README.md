# PowerVR Graphics WebGL SDK #
![WebGL Water demo screenshot](http://powervr-graphics.github.io/WebGL_SDK/images/WebGLWaterDemo.png)
This repository contains the source code for the PowerVR Graphics WebGL SDK. Although the WebGL SDK is written from the ground up in Javascript, it retains the coding style of the native C/C++ PowerVR Graphics OpenGL ES SDK. This should make the code instantly recognisable to programmers who have used our OpenGL ES SDK before.

The WebGL SDK includes an abstraction layer that handles application life-cycle events (Shell), a 3D maths, text printing and resource loading framework (Tools), and a sub-set of the native OpenGL ES SDK's 3D graphics example applications. The SDK has been optimized for PowerVR devices, but should run efficiently on all WebGL capable phones, tablets, laptops and PCs.

If you would like to know more about the WebGL SDK, please visit our [SDK Browser](http://powervr-graphics.github.io/WebGL_SDK/WebGL_SDK/SDKBrowser.html).

To keep up to date with changes to the SDK read the [what's new](http://community.imgtec.com/developers/powervr/whats-new/) page.

## Setup ##
Many of the WebGL Examples require the code to be hosted on a server. For demonstration purposes we've used GitHub's [Pages feature](https://pages.github.com/) to host the WebGL SDK. If you fork the code on GitHub you can use the same mechanism to host your modified code. If you would prefer not to use GitHub, you will need to host the code on your own web server.

### Beginner ###
<ol>
<li><a href="http://powervr-graphics.github.io/WebGL_SDK/WebGL_SDK/Examples/Beginner/01_HelloAPI/WebGL/">01_HelloAPI</a></li>
<li><a href="http://powervr-graphics.github.io/WebGL_SDK/WebGL_SDK/Examples/Beginner/02_IntroducingPVRShell/WebGL/">02_IntroducingPVRShell</a></li>
<li><a href="http://powervr-graphics.github.io/WebGL_SDK/WebGL_SDK/Examples/Beginner/03_Texturing/WebGL/">03_Texturing</a></li>
<li><a href="http://powervr-graphics.github.io/WebGL_SDK/WebGL_SDK/Examples/Beginner/04_BasicTnL/WebGL/">04_BasicTnL</a></li>
<li><a href="http://powervr-graphics.github.io/WebGL_SDK/WebGL_SDK/Examples/Beginner/05_IntroducingPVRTools/WebGL/">05_IntroducingPVRTools</a></li>
<li><a href="http://powervr-graphics.github.io/WebGL_SDK/WebGL_SDK/Examples/Beginner/06_IntroducingPrint3D/WebGL/">06_IntroducingPrint3D</a></li>
<li><a href="http://powervr-graphics.github.io/WebGL_SDK/WebGL_SDK/Examples/Beginner/07_IntroducingPOD/WebGL/">07_IntroducingPOD</a></li>
</ol>
### Intermediate ###
<ol>
<li><a href="http://powervr-graphics.github.io/WebGL_SDK/WebGL_SDK/Examples/Intermediate/RenderToTexture/WebGL/">RenderToTexture</a></li>
</ol>
### Advanced ###
<ol>
<li><a href="http://powervr-graphics.github.io/WebGL_SDK/WebGL_SDK/Examples/Advanced/Water/WebGL/">Water</a></li>
</ol>

## License ##
The SDK is distributed under a permissive license so it can easily be integrated into commercial and non-commercial applications. You can find the license [here](https://github.com/powervr-graphics/WebGL_SDK/blob/master/LICENSE.txt). To further clarify the terms, we also have an SDK license FAQ (available [here](http://community.imgtec.com/developers/powervr/faq-about-the-sdk-eula/)).
