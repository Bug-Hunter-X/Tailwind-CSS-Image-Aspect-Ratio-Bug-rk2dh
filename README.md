# Tailwind CSS Image Aspect Ratio Bug

This repository demonstrates a common issue encountered when using fixed width and height for images in Tailwind CSS.  If the image's aspect ratio doesn't match the specified dimensions, the image will be distorted.

## Bug

The `bug.html` file contains the code that exhibits the problem.  Notice how the image is stretched or squished depending on its original aspect ratio.

## Solution

The `solution.html` file showcases how to properly handle image aspect ratios using Tailwind CSS's object-fit utility.  This ensures the image is displayed correctly without distortion, maintaining its original aspect ratio.