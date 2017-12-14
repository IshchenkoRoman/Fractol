# Fractol

## Intoduction
The term fractal was first used by mathematician Benoit Mandelbrot in 1974,
he based it on the Latin word fractus, meaning "broken" or "fractured".
A fractal is an abstract mathematical object, like a curve or a surface, which has a similar
pattern whatever the scale.

## Objectives
Now that you took over your first graphical library: the **miniLibX**,
it’s time for you to light all the pixels of your screen at the same time!
This new project will be the opporunity for you to hone your miniLibX skills, to make
you discover/use the mathematical notion of complex numbers and to take a peek at the
concept of optimization in computer graphics.

## General Instructions
 1.  The executable file named fractol.
 2.  Makefile must compile the project and must contain the usual rules. It does not recompile and re-link the program unless necessary.
 3.  This project use the **miniLibX**. Either in the version that is available on the system, or from its sources.
 4.  This project use the following functions:
     - 1) open, read, write, close
     - 2) malloc, free
     - 3) exit
     - 4) functions defined in the math library (-lm and man 3 math)
     - 5) functions defined in the **miniLibX** library.
 ## Mandatory part
1. The software offer at least 4 different types of fractals: **Julia
set**, the **Mandelbrot set**, **Burning Ship set**, **Newton set (Newton pool)**.
2. It possible to make the parameter of the Julia set vary only with the mouse
(without clicking).
3. The mouse wheel zooms in and out, almost infinitely (within the limits of the
computer).
4. It used 16 colors to show the depth of each fractal. It’s even better
if you hack away on psychedelic effects.
5. A parameter is passed on the command line to define what type of fractal will be
viewed. If no parameter is provided, or if the parameter is invalid, the program
displays a list of available parameters and exits properly.
6. ESC will exit the program also as red cross.
7. Use of images of the minilibX.
 ## Bonus part
 
 -  [X] The zoom follow the actual mouse position.
 -  [X] In addition to the zoom: moving with the arrows.
 -  [X] Make the color range shift.
 -  [X] Multi-threading implementation. (used pthread)
 -  [X] Two valid parameters in the command line, resulting in two fractals in two windows.
 ## How to use
 
```
https://github.com/IshchenkoRoman/Fractol
cd Fractol
make
./fractol param1 param2 param3 param4

Where param[1 - 4] represent one of sets. Minimum count of paramters is 1.
```
_Pressed **CTRL** allow you change paramaters of Julia's set with moving mouse in window._
_One more time **CTRL** block able to change set._

To change the set on antoher you can press **1**, **2**, **3** or **4** where 
1. Julia
2. Mandelbrot
3. Burning ship
4. Newton pool

Also every fractal remember his own position. That's mean you can freely change every fractal in one window.

For reset to default position use **R**.

In Burning ship you can see psychedelic effects- just press _space_ and don't release it.
**WARNING** Be careful this effect strongly hit eyes and don't reccomend people with epilepsy.

## Showtime

<img width="1312" alt="screen shot 2017-11-30 at 9 26 59 pm" src="https://user-images.githubusercontent.com/30857998/34019906-031079d4-e129-11e7-86cc-73b046c18b63.png">
<img width="1312" alt="screen shot 2017-11-30 at 9 13 13 pm" src="https://user-images.githubusercontent.com/30857998/34019907-03f0c28c-e129-11e7-9f73-e8324c2d71c6.png">
<img width="1312" alt="screen shot 2017-11-30 at 9 26 08 pm" src="https://user-images.githubusercontent.com/30857998/34019911-04cbdaa2-e129-11e7-8a7a-49a3a1ae9ab7.png">
<img width="1312" alt="screen shot 2017-11-30 at 9 13 44 pm" src="https://user-images.githubusercontent.com/30857998/34019912-0598bc8e-e129-11e7-8599-50901d4c0fcf.png">
