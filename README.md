# Lab2: Your Weight on Other Planets

## Objectives

- Review the basic object-oriented concepts: class and class instantiation.
- Learn how to create classes and objects in Java.

## Work

1. Review Lab2.java, which includes `main()`. You don't need to make any changes to this file.
2. Complete the `Planet` class in the `Planet` file.
3. Complete the `PlanetData` class in the `PlanetData` file.

    ![](Lab2_IMages/Lab2_Window.jpg)

## To Complete Planet Class

1. Declare the following private variables:
- `String name`
- `ImageIcon image`
- `double surfaceGravity`

2. Define the following public constructor, which assigns the arguments to the local variables.
- `Planet(String name, ImageIcon image, double surfaceGravity)`

3. Define the following methods:
- `String getName()`
- `ImageIcon getImage()`
- `double getSurfaceGravity()`
- `double calculateWeight(double mass)`

4. The weight is calculated by mass * surfaceGrfavity.

## To Complete PlanetData Class

1. Declare the following private variable:
- `Planet[] data`

2. Define the following public constructor, which instantiates the class `Planet` with `String name`, `ImageIcon image`, `double surfaceGravity` for each planet and assigns the data collection  to `data`.
- `PlanetData()`

3. Use the following name, image and surfaceGravity (g) for the planets:

| name | image (*1) | surfaceGravity |
|---|---|---|
| Mercury | mercury.gif | 0.377 |
| Venus | venus.gif | 0.905 |
| Moon | moon.gif | 0.1654 |
| Mars | mars.gif | 0.379 |
| Jupiter | jupiter.gif | 2.528 |
| Saturn | saturn.gif | 1.065 |
| Uranus | uranus.gif | 0.886 |
| Neptune | neptune.gif | 1.137|
| Pltuto | pluto.gif | 0.063 |

(*1) Use `new ImageIcon("../Lab2_Images/planet.gif")`.

4. Define the following public methods:
- `Planet[] getData()`
- `String[] getNameList()`

---
End of Lab2
