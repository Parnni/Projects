# Project - Mechanical Vibrations using RK method.

## Table of Contents
- [Overview](#Overview)
- [Motivation](#Motivation)
- [Prerequisites](#Prerequisites)
- [Technologies Used](#Technologies-Used)
- [Result](#Result)
- [Credits](#Credits)

## Overview
The project focuses on solving SDOF vibration equation with no external force using
1. Euler's Method.
2. Runge-Kutta's method. 
We will learn the reason why we used Runge-Kutta's Method.

## Motivation
I was trying to solve some Engineering problems using Numerical Methods and there I came across Euler's Method of Integration.
I applied it on the SDOF vibration equation but the result was unsatisfactory.
<img src="https://github.com/Parnni/Projects/blob/main/Mechanical%20Engineering/Images/EulerEnergy.PNG">
It is clear from the image above that the Energy is increasing which shouldn't happen. So, which Numerical Method should I choose to avoid 
this problem?
This led me to Runge-Kutta's Method.

## Prerequisites
- You should be familiar with SDOF vibration equation.
- You should be familiar with vectors.
- You should be familiar with the working of Euler's and Runge-Kutta's Method.
- You should be familiar with Python or Jupyter.

## Technologies Used
Jupyter Notebook

## Result
After applying Runge-Kutta's Method on the equation the result is as follows
<img src="https://github.com/Parnni/Projects/blob/main/Mechanical%20Engineering/Images/RKEnergy.PNG">
As we can see from the image above that the Energy remains constant.

## Credits
I learned the Runge-Kutta's Method from a YouTube channel named [Good Vibrations with Freeball](https://www.youtube.com/watch?v=IOkwWYaZbck&list=PL2ym2L69yzkZJ1fY3SQ1JCyvZIoJYXQGZ&index=12)
