The networks correspond to:

0: Jan18_320x180_base (first UNET, depth=4, Upsample, ADAM)
1: Jan18_320x180_convt2d (first UNET, depth=4, Convt2d, ADAM)
2: Jan21_640x320_unet2 (second UNET, depth=5, ADAM)
3: Jan22_640x320_cyclic_SGD (second UNET, depth=5, SGD, cyclic learning rate)
4: Jan25_640x360_cyclic_adam (second UNET, depth=5, ADAM, cyclic learning rate)