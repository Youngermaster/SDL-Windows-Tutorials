# SDL-Windows-Tutorials

This repo contains some examples and tutorials with SDL on Windows, 
of course you can use this cpp codes on Linux or Mac, although this README.md
doesn't cover how to setup those examples.

## Setup

### Note: Make sure Visual Studio is installed.

First of all go to the [SDL web page](https://www.libsdl.org), go to releases

<p align="center">
    <img src="GitHubAssets/Step_1.png">
</p>

And download the Visual Studio version

<p align="center">
    <img src="GitHubAssets/Step_2.png">
</p>

Also download the [`SDL Image library`](https://www.libsdl.org/projects/SDL_image/), the Visual Studio version in this case.

<p align="center">
    <img src="GitHubAssets/Step_3.png">
</p>


Then **unzip those folders wherever you want**.


Let's go to Visual Studio, create a new `C++` project and then click on propperties

<p align="center">
    <img src="GitHubAssets/Step_4.png">
</p>

Go to `VC++ Directories`, fill the `Include Directories` and the `Library Directories` with the folder path of the folders that you unzipped.

### Note: select `x64` or `x86` deppending of the type of build settings you have or want.

<p align="center">
    <img src="GitHubAssets/Step_5.png">
</p>


Go to `Linker` and click `Additional Library Directories`, then add the `lib` folder of the unzipped folders.

<p align="center">
    <img src="GitHubAssets/Step_6.png">
</p>

Let's go to the `input` section in the `Linker`, and add the following text:
<p align="center">
    <img src="GitHubAssets/Step_7.png">
</p>

And after all we almost got it, maybe in some PC's would work just using the last step, but, if it doesn't work, let's do the following steps.

Go to the `lib` folder of both unzipped folders and paste it to the folder where you are running your project, like this:

<p align="center">
    <img src="GitHubAssets/Step_8.png">
</p>

<p align="center">
    <img src="GitHubAssets/Step_9.png">
</p>

And after that we can get something like this:

We move it with `W`, `A`, `S`, `D`.
<p align="center">
    <img src="GitHubAssets/Step_10.gif">
</p>