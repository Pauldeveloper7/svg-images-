# SVG Image Usage Guide

Welcome to the SVG Image Usage Guide! This guide provides instructions on how to use an SVG image, along with an example HTML page demonstrating its usage.

## Files Included

- `svg_image.pdf`: This PDF file contains a  guide on how to use SVG images.
- `example_image.svg`: This is the SVG image file that you can use in your projects.
- `index.html`: An HTML file demonstrating how to include and use the SVG image.

## How to Use the SVG Image

1. **Read the Guide**: Start by reading the `svg_image.pdf` file for detailed instructions on using SVG images. It covers topics such as SVG syntax, shapes, attributes, and styling.

2. **Download the SVG Image**: Download the `example_image.svg` file to your local machine. This SVG image will be used in the example HTML page.

3. **Include the SVG Image in Your Project**: Copy the `example_image.svg` file into your project directory.

4. **Embed the SVG Image in HTML**: Open your HTML file and include the SVG image using the `<img>` tag or by directly embedding the SVG code into your HTML.

   ```html
   <!-- Using <img> tag -->
   <img src="example_image.svg" alt="Example SVG Image">

   <!-- Directly embedding SVG code -->
   <svg width="100" height="100">
     <use xlink:href="example_image.svg#svg-shape"></use>
