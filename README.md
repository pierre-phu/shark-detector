# shark-detector
A project allowing to detect sharks (and other marine animals) from above (drone video)

## Wanna try it with your own computer on a Youtube video ?
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install all the dependencies.

```bash
pip install torch torch-vision cv2 pafy
```

Once everything is set up, just change the yt_adress string located at the top of the shark_detector.py file

```python
import torch
import numpy as np
import cv2
import pafy
from time import time

# Change this parameter to apply the detector on a youtube video
yt_adress = "https://www.youtube.com/watch?v=TX2d5sWbiyY"
```


## What if I want to apply it to my own video ?

The easiest way is to upload your video on Youtube and then use the first method.
You can make it accessible with link-only on Youtube if you want to keep it more private.
