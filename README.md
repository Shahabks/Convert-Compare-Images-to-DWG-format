# Convert-Image-to-DWG-format
## Converting a raster or a vector image to DWG 
## Distance-based functions for image comparison

![Image](https://github.com/Shahabks/Convert-Image-to-DWG-format/blob/master/Images/left.png)
![Image](https://github.com/Shahabks/Convert-Image-to-DWG-format/blob/master/Images/right.png)
![Image](https://github.com/Shahabks/Convert-Image-to-DWG-format/blob/master/Images/leftright.png)


## How to convert to DWG
So, you’ve heard a lot about why you should convert your image to DWG – but how do you actually go about doing it? 
With a quite intiutive algorithm, converting to DWG from almost any file type is easy – here are some of the bases for the conversions. 

### How does the conversion process work? 
The conversion process can be completed in one of two ways: manual or automatic tracing. Each have their own advantages and 
disadvantages.

### Manual tracing
This process involves tracing over the entire image by hand. This can be done by using a mouse to trace over every line, or by 
using a tablet and graphics pen to draw over the raster. This process has quite a few advantages. It has the added benefit of 
human understanding being the driving force behind it—conversion software won’t be able to figure out what a faded line means, 
and will just ignore it, whereas you have the knowledge of what the drawing should look like. This means that you can work with 
images of any quality, because you’re familiar with the drawing or you can make a well-informed guess.

![Image](https://github.com/Shahabks/Convert-Image-to-DWG-format/blob/master/Images/manual-tracing-raster1.png)

There are a few setbacks to this process, however, as it can be very long and strenuous. The more complex the image is, the more 
time it will take. Plus, despite the higher level of understanding, humans are still rather inaccurate—a computer is efficient and 
precise by comparison. 

### Automatic tracing
Raster to Vector Conversion - the algorithm process detects the lines and edges of your raster image and redraws them as vector lines,
curves, polygons and other vector entities. It has many advantages over manual tracing: for starters, it is a very speedy process 
takes mere seconds to convert! Meanwhile, OCR tools are perfect for dealing with any text that may appear in your PDF file, and can 
convert it to editable text.

![Image](https://github.com/Shahabks/Convert-Image-to-DWG-format/blob/master/Images/raster-to-vector-conversion-300x207.png)

If you’re at the mercy of tight deadlines, and you’re working with relatively simple raster images, it’s definitely beneficial to 
make use of automatic conversion software. 

### Raster image formats to DWG
Converting from a raster format—such as PNG, JPG, or TIFF—to DWG could be thought of as a more intelligent process. Your conversion 
software has to first detect lines, shapes, text and other entities present in the image – a process which includes deciding on 
the appropriate entity type. It must then trace over the pixels in the raster image with vector entities. If you had to do all this 
manually, it would take an age. Luckily, the algorithm makes the process quick and easy.

### PDF to DWG
Although PDF is one of the most common file types in the world, PDFs can be surprisingly complex. Each page in a PDF can contain any 
combination of 2D vector graphics, text, or raster images. Converting from PDF to DWG therefore involves two different processes: 
extracting existing vector information, and vectorizing raster images within the PDF. The algorithm is capable of both – and also enables 
you to import vectors only, rasters only, or both.

PDFs are great for viewing vector images, but the vector graphics they contain are very limited, and can’t usually be understood by 
CAD programs. Converting to DWG with the algorithm, however, produces vector entities which can easily be edited using CAD software. 
This algorithm preserves the vector information present within the PDF, including colors, line types, and line widths. Not only that, but it 
arranges text into easily editable strings, and is able to create vector arcs and circles – entity types which do not exist in PDFs. 
Once the vector information has been extracted, just export the file as a DWG.

A circle vectorized from a PDF by another converter	A circle vectorized from a PDF 
These circles were imported from a PDF using another conversion program. Instead of appearing as two vector circles, they have been 
reproduced as a series of small vector lines, making them very hard to edit in CAD.	These circles were imported from a PDF using 
the algorithm. This algorithm detected them and reproduced them as easy-to-edit vector circles. When importing your PDF, 
just click File > PDF > Import Options… > Make Vector Circles
In addition to the vector entities, your PDF may also include raster images. If you wanted to edit these images in CAD, 
you would need to vectorize them. PDFs may also include multiple raster images on a single page. For example, some scanners 
create “stripped” PDFs made up of many horizontal strips rather than a single image. This algorithm maps all of these into a single raster 
image per page, whilst preserving the quality of the image. Once you’ve imported your raster images from the PDF, simply vectorize
them as you would any other raster format, then save as a DWG.

### Absolute Difference
The image difference of two images is defined as the sum of the absolute difference at each pixel. The first image It is analyzed 
with a second image,It–T, at a temporal distance T. The difference value is defined as

![Image](https://github.com/Shahabks/Convert-Image-to-DWG-format/blob/master/Images/1.png)

where M is the resolution or number of pixels in the image. This method for image difference is noisy and extremely sensitive to 
camera motion and image degradation. When applied to subregions of the image,D(t) is less noisy and may be used as a more reliable 
parameter for image difference.

![Image](https://github.com/Shahabks/Convert-Image-to-DWG-format/blob/master/Images/2.png)

Ds(t) is the sum of the absolute difference in a subregion of the image, where S represents the starting position for a particular 
region and n represents the number of subregions.

We may also apply some form of filtering to eliminate excess noise in the image and subsequent difference. For example, the image on
the right in Fig. below represents the output of a Gaussian filter on the original image on the left.

![Image](https://github.com/Shahabks/Convert-Image-to-DWG-format/blob/master/Images/ex1.png)
![Image](https://github.com/Shahabks/Convert-Image-to-DWG-format/blob/master/Images/ex2.png)
![Image](https://github.com/Shahabks/Convert-Image-to-DWG-format/blob/master/Images/ex12 RESULT worn-out FONT diff
.png)
