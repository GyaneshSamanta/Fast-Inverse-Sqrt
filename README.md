# A Quake III Algorithm 
- Whilst implementing physics, lighting or reflections in a game engine, it is helpful if the vectors that are being dealt with are normalised to length one.   

- Length of the vector _`L = {x/sqrt(x^2+y^2+z^2)}`_ Similarly for y and z.  

## Problem Statement 🛠

- To reduce the time taken to calculate squareroot of a number and hence make normalized vector calculations faster.  

## Background 📑

- Addition and Multiplication operations are common operations and are generally rapid. But when it comes to the [sqrt](https://www.geeksforgeeks.org/sqrt-sqrtl-sqrtf-cpp/) function, the operation is much slower. P.s Division is not much better either. 

- Here, we try to find the approximate value of square-root without actually using the square root function. This approximate value is within an error of 1% of the actual value. The TLDR of this operation is; as long as it's fast, we can save a lot of precious time. 

## Result ☑️
-  The algorithm is approximately 3 times as fast with an 1% error margin with respect to the square root function. 

## Talk Nerdy to me 💻





