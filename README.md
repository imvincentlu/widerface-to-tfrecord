fork from https://github.com/yeephycho/widerface-to-tfrecord
# widerface-to-tfrecord
parse [WIDER FACE](http://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/) dataset to tensorflow tfrecord format for object detection api.

# Dependencies
numpy

opencv 3.5

tensorflow > 1.0.1

# Usage
## Create simbolic link to WIDER FACE dataset
Unzip .zip file to folder "\~/WIDER/WIDER_train" and make sure "wider_face_train_annot.txt" is under folder "\~/WIDER".

``` bash
ln -s ~/WIDER ./widerface-to-tfrecord/WIDER
```

## Run the script
``` python
python widerface_To_TFRecord.py
```
