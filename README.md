# Tensorflow_ocr
Using tensorflow on chinese OCR


### Install tensorflow on Linux
Install by anaconda
Fixed the command error
`export PATH=~/anaconda3/bin:$PATH`

Environment: Ubuntu 16+; Python 3.6; Tensorflow-CPU

Finished testing Tensorflow OCR by SpikeFlow; recognition result even lower than tesseract. Plus, Spike using openCV to train single word. It is not worth to do that.

### Trained data problem
    once cp file to the usr/local/share/tessdata dir, make sure cp the full trained data into this dir.

    make sure download osd and equ traineddata

    and set environment `export TESSDATA_PREFIX=/usr/local/share/tessdata`


    

