# Approximation of a Bézier Curve length 

## Description
A Jupyter notebook that builds a formula to approximate the length of a Bézier Curve without calculating the curve. The purpose of this is on the one hand submitting it as part of a paper for my university study and on the other hand optimizing 
[my OpenSCAD Bézier Curve code](https://benjaminwand.github.io/verbose-cv/projects/bezier_curves.html). 

So far only Cubic Bézier Curves in zwo dimensions are covered but I might add others later since I use 3d curves and different orders as well.

## Requirements
* [Jupyter notebook](https://www.studytonight.com/post/how-to-install-jupyter-notebook-without-anaconda-on-windows)
* Python 3.12.7

## Spoiler
Given a curve with points labeled as such:
![abb1.png](abb1.png)
The formula for curves with three, four and five control points are:
![lengthformula.jpg](lengthformula.jpg)