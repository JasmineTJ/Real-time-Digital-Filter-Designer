# Realtime Digital Filter Design

This project is a desktop application that assists users in designing a custom digital filter via zeros-poles placement on the z-plane. 

## Features

### Z-Plane Plot

The application provides a plot for the z-plane with the unit circle, where users can place different zeros and poles. Users can also:

- Modify the placed zeros/poles by dragging them.
- Click on a zero or pole and delete it.
- Clear all zeros, clear all poles, or clear all.
- Choose whether to add conjugates for the complex elements.

### Frequency Response Plot

The application shows the corresponding frequency response for the placed elements. It includes one graph for the magnitude response and another graph for the phase response.

### Real-Time Filtering

Upon finishing the filter design and visualizing the filter response, users can apply the filter on a lengthy signal as if it is a real-time filtering process. The application provides:

- A graph that shows the time progress of the signal.
- Another graph to show the time progress of the filtered signal.
- A control for the speed/temporal-resolution of the filtering process. For example, the filter can process 1 point per second or 100 points per second or any number in between via a slider.
- An option to input an arbitrary real-time signal via moving the mouse on a small padding area. The input signal would be the x- or y- dimension of the mouse coordinate. The faster the user moves the mouse, the higher frequencies the generated signal will have and vice versa (i.e., slower motion → low frequencies).

### Phase Correction

Users can correct for the phase by adding some All-Pass filters. The application provides:

- A library of all-pass filters that the user can visualize (its zero-pole combination as well as its phase response), then pick one or more to add to the original design filter.
- A custom-built all-pass: if the user cannot find a good all-pass in the provided library, then they can build their own. i.e., provide an arbitrary “a” and the application would calculate its phase response and integrate it with its library.
- An option to enable/disable the added all-pass elements via a drop-menu or checkboxes group.

## Preview
<img src = 'Preview 1.png'>
<img src = 'Preview 2.png'>