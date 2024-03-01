# Counting-White-Blood-Cells-
A project aimed to outline the nucleus of white blood cells from blood smear images and count them.

If your expected outcome is similar to what is shown in 'final image and count.png', download the COUNTS.ipynb file and run it on your system.
It includes an interface that allows you to select an image from your machine.

A brief explanation of 'COUNTS.ipynb' is present in the PDF.

'Alternate Counts function.ipynb' contains a getCounts2() function similar to getCounts() (present in 'COUNTS.ipynb'), where the former extracts more information from the outlined shape such as radius, perimeter, circularities, bounding boxes, aspect ratios, extents, convex hulls, moments and fit ellipses.
These extra properties are the additional features extracted from the outlined image, that can be used on machine learning models.

Replace 'getCounts()' with code from 'getCounts2()' for extraction of the additional information.
