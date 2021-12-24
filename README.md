# RNNoise is a noise suppression library based on a recurrent neural network

[![Open 3DPhotoInpainting in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1e880USU8IcZWZlEJYfyeu9DNVGxpNd06)

## Quick Demo application
While it is meant to be used as a library, a simple command-line tool is
provided as an example. Here is a [Colab Demo](https://colab.research.google.com/drive/1e880USU8IcZWZlEJYfyeu9DNVGxpNd06) to Convert Raw Noised Audio to Cleaned Audio. 

### build librnnoise & rnnoise_demo with CMake

```shell
# mkdir build
# cd build
# cmake ..
# make
```

It operates on wav and mp3 files, which can be used as:
```shell
# ./rnnoise_demo input.wav
# ./rnnoise_demo input.mp3
```

the output filename is "input_out.wav"
or:

specify the output filename
```shell
# ./rnnoise_demo input.wav output.wav
# ./rnnoise_demo input.mp3 output.wav
```

# References and Resources:
- [david8862/rnnoise](https://github.com/david8862/rnnoise)
- [RNNoise: Learning Noise Suppression](https://people.xiph.org/~jm/demo/rnnoise/)
- [RNNoise: Learning Noise Suppression（深度学习噪声抑制）](https://blog.csdn.net/dakeboy/article/details/88039977)
- [基于RNN的音频降噪算法](https://cloud.tencent.com/developer/article/1094567)
- [ZhiHan Gao](https://github.com/cpuimage/rnnoise)

## License
This work is licensed under MIT License. See [LICENSE](LICENSE) for details. 

# Donating

If you found this project useful, consider buying me a coffee

<a href="https://www.buymeacoffee.com/athenasaurav" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/black_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
