# landmark-classifier-js

A Tensorflow.js demo based on [Tensorflow.js MobileNet demo](https://github.com/tensorflow/tfjs-examples/tree/master/mobilenet)

The model is a simple ConvNet model, trained in Tensorflow and [converted](https://www.tensorflow.org/js/guide/conversion) to tfjs, capable of classifying four buildings:
 - Oriental Pearl TV Tower, Shanghai, China
 - Band of China Building, Hong Kong S.A.R.
 - Empire State Building, New York, NY
 - Reichstag Building, Berlin, Germany
  
## Usage
Clone and serve this directory with any web server, e.g.,
```
python3 -m http.server [port]
```

Upload a photo of any one of the buildings above and see the results. Train/val dataset is very small and validation accuracy is around 70%.
