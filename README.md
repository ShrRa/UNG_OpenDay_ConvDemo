A convolution demo for the UNG Open Day 2025. Can be run within Jupyter Lab environment (running all cells in the `ConvolutionDemo.ipynb` 
file should do the trick and display the interface at the bottom of the notebook) or by launching `panel serve ConvolutionDemo.ipynb --dev`
from the command line (don't forget to activate the virtual environment that has all the dependencies installed). The demo contains three tabs:
1) For launching convolution with one of three kernels
2) For convolving the image patch by patch
3) To combine three convolutions into a single RGB image.

### Requirements
- panel
- cv2
- PIL
- bokeh
- matplotlib
