# RNNOISE-COLAB DEMO

[![Open 3DPhotoInpainting in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lBx156kISjDKdMNZBV5UiPQNPLRN9Ld2)

RNNoise is a noise suppression library based on a recurrent neural network.

# Quick Demo application

While it is meant to be used as a library, a simple command-line tool is provided as an example. Here is working [Colab Demo](https://colab.research.google.com/drive/1lBx156kISjDKdMNZBV5UiPQNPLRN9Ld2?usp=sharing) to clean RAW Noisy input and get cleaned Output

build librnnoise & rnnoise_demo with CMake

```
# mkdir build
# cd build
# cmake ..
# make
```

It operates on wav and mp3 files, which can be used as:
```
# ./rnnoise_demo input.wav
# ./rnnoise_demo input.mp3
```

## License
This work is licensed under MIT License. See [LICENSE](LICENSE) for details. 
