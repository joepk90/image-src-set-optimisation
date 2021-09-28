# Image Src Set Optimisation

### Simple Working Example
Control the image source depending on the device width, pixel densities and available image format:
- https://joepk90.github.io/image-src-set-optimisation/

### Advanced Working Example
Control the image source depending on the device width, pixel densities and network conditions. Image formats and device type could also be incorperated:
- https://joepk90.github.io/image-src-set-optimisation/javascript-write.html

To comapare the same setup without the network condition logic, see the following example:
- https://joepk90.github.io/image-src-set-optimisation/javascript-write-compare.html

### Other Examples (Not working)
The following two examples looks at using the browsers network connection to further control the selected image source. However Using Javaascript to control the image source effects the LCP. In some scenereos the image is requested after DOMContentReady:
- https://joepk90.github.io/image-src-set-optimisation/javascript-sibling.html
