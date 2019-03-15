Build Instruction:
```
mbed import https://github.com/neil-tan/tf_microspeech
cd tf_microspeech/
mbed compile -m DISCO_F746NG -t GCC_ARM --profile=tflm/tensorflow/lite/build_profiles/release.json
```