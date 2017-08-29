
## Digitization Standards

The **BUDA** project currently purchases Buddhist digital texts meeting the following requirements: 

The images of a work are presented in two formats: 1) the archival images and 2) the web images. The web images are derived from the archival images, and both sets of images are kept within a "work folder". Image names, cropping, and orientation should match in both image sets; whole file size, format, color depth, DPI, and compression may be different. Check out the sample files here: [single volume](haha.jpg), [multiple volume](haha.jpg)).


**Archive Image Requirements**

| Feature | Standard | 
| ------------ | ------------- | 
| File format | JPEG 2000 (**.j2k**), wavelets compression, highest data size
| Resolution | 600 ppi/dpi |
| Color profile | RGB, 24-bits |
| Pixel dimensions | consistent width |
| Quality | 1 page per image, no borders, no scan lines, no artifacts

**Web Images Requirements**

| Feature | Standard | 
| ------------ | ------------- | 
| File Format | JPEG (**.jpg**) for color pages, TIFF G4 compression (**.tif**) for text only pages 
| Resolution | consistent ppi/dpi |
| Color Profile | RGB 24-bits for JPEG, BW 1-bit for TIFF |
| Pixel dimensions | consistent width |
| File size | smaller than 400 KB | 

**Folder Structure** 

📂 **AB0001** *- work folder named with the current text's Accession Number*

* 📄 **AB0001.xlsx** *- "Bibbliographic Info Sheet" in Excel format*
* 📂 **archive** *- large size images for long term archival*
    * 📂 **01** *- volume 1 folder. One folder per volume*
        * 🖼 **0001.j2k** *- cover image in JPEG2000, RGB, wavelets compression*
        * 🖼 **0002.j2k** *- text image in JPEG2000, RGB, wavelets compression*
        * 🖼 **0003.j2k** *- ...*
    * 📂 **02** *- volume 2 folder*
        * 🖼 **0001.j2k**
        * 🖼 **0002.j2k**
    * 📁 **03** *- ...*

* 📂 **images** *- small size web images for the website and the apps*
    * 📂 **01**
        * 🖼 **0001.jpg** *- cover image in JPEG, RGB, JPEG compression*
        * 🖼 **0002.tif** *- text image in TIFF, BW, G4 compression*
        * 🖼 **0003.tif** *- ...*
    * 📁 **02**
    * 📁 **03**