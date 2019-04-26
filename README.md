# Plot curly brace with matplotlib

The purpose of this project is to allow easy plotting of curly brace between two points when using matplotlib.

This feature is not built into matplotlib (also, not MATLAB, but there is a very good implementation on File Exchange), and thus the motivation. The author has found some previous implementations, but none would do what the author would like to do, i.e., give the function the xs and ys of two points of
the axes and plot a curly bracket with text annotation at the summit of the bracket. Therefore, the author decided to write one.

The implementation here is based largely on the implementation by [Pål Næverlid Sævik](https://uk.mathworks.com/matlabcentral/fileexchange/38716-curly-brace-annotation) for MATLAB (can be found on File Exchange). Some modifications are done for Python purposes. Some addition features have been implemented, e.g., allow text annotation, negative log (for 'symlog' scale in matplotlib).

This project is built with Python 3.7.1, matplolib 2.2.3 and numpy 1.15.4.

Tested on Windows 7.

The following is an example of plotting two curly brackets to annotate a sine wave.

![Example](build/html/_sources/img/exp.jpg)

## Main features

* **Allows intuitive plotting of a curly bracket between two points within the given axes of the given figure** 
* **Allows text annotation to be placed at the summit of the bracket with the same rotation as the bracket**
* **The height of the bracket can be controlled**
* **Accepts line settings for the bracket lines (same as matplotlib via named parameters, e.g., line width, line colour, etc.)**
* **Accepts font settings of the annotating text (same as matplotlib, just give a fontdict)**
* **Works with linear axes and log axes**
* **Transformation between axes coordinates and screen coordinates can be turned on or off**

## Prerequisites

* **Python 3.5+**
* **maplotlib**
* **numpy**

## Version

**1.0.1**

## Example

### Annotating sine waves

![Example](build/html/_sources/img/exp_sin.png)

### Annotating circles

![Example](build/html/_sources/img/exp_circle.png)

### Annotating log scale

![Example](build/html/_sources/img/exp_log.png)

### Annotating ellipses

![Example](build/html/_sources/img/exp_ellipse.png)

### Annotating astroids

![Example](build/html/_sources/img/exp_astroid.png)


## Contributing

高斯羽 博士 (Dr. Gao, Siyu)