# Par0042 - elastix

###  Image data

* MRI
* Short Tau Inversion Recovery (STIR) sequence
* Voxel size: ~ 0.742 x 0.742 x 4.4 mm

###  Application

* The registration was used for atlas-based segmentation of vertebral bodies.

###  Registration settings

`elastix` version: 4.600

Parameter files:

See Github link below.

Description:

* Aligns the atlas image to the target image

Command line call:


    elastix -f TargetImage.mhd -m AtlasImage.mhd -p par0042rigid.txt -p par0042bspline.txt -out outputdir
