---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.12
    jupytext_version: 1.6.0
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Numpy and Scipy

In this section we introduce the `numpy` and `scipy` packages that you will certainly use and will need to know for this course. 

`numpy` focuses on the efficient manipulation of structured data that in many languages would already be included as some sort of *array* data type. `numpy` provides routines to do many operations on arrays of data such as sorting, finding the largest or smallest element, transposing data and so on. It also provides many mathematical operations including the expected (element-by-element) functions (trigonometry, exponentials etc). 

`numpy` also provides an extensive overloading of the standard operators for manipulating lists of data (etc) that make array operations quite natural and compact in python. It is very important to understand what `numpy` is doing because it is almost impossible to avoid close encounters with these operators in everyday python. 

`numpy` has been very carefully optimised and, used correctly, will give you access to very efficient (mostly that means *fast*) code without having to leave the python environment. This means you should always look to see if there is a `numpy` function to do what you need *and never write a python loop if you can help it*. 

  - [Introduction To Numpy](1-IntroductionToNumpy.md) - This notebook goes into more detail about why we need `numpy`, what the operator overloading looks like, and explores the speed benefits of using `numpy`. The other benefits are readability of your code (as long as you understand the operator overloading) and reliability because you are using pre-built code, not writing your own loops. 
  - [The game of life 1](2-Application-TheGameOfLife.md) - This notebook sets up an exercise: the game of life, to show how `numpy` works in a real problem. We will see how to approach problems of structured data so that we can most of the work efficiently with `numpy`.
  - [The game of life 2](3-Discussion-TheGameOfLife.md) - Here we have a chance to reflect on the choices we made in the previous notebook and think about how things could be done better (or differently, anyway). 

  These notebooks are not intended to be comprehensive because you will have lots of opportunity to practice looking at `numpy` code when we look at satellite images and basemaps in the [`cartopy` mapping](Notebooks/Themes/Mapping/0-Maps_with_Cartopy.md) examples, and the [`stripy` spherical meshing](Notebooks/Themes/SphericalMeshing/0-Stripy.md) examples. 

  `scipy` is a collection of useful algorithms loosely bundled together. If you have ever come across the book "Numerical Recipes" then you will know what `scipy` is trying to do: there is usually some reasonable implementation in `scipy` for whatever problem you are faced with: interpolation, optimisation, meshing, image manipulation. It is neither comprehensive nor definitive but, like a Swiss-Army Knife, more useful in a pinch than most other tools.

   - [Introduction](4-IntroductionToScipy.md) - Really just a list of modules that `scipy` provides. Each of the modules is a collection of related functionality that has a mostly-consistent user interface. 

