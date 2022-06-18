# Ascii-Art-Generator-and-Pencil-sketch

This is an image processing project in which we will covert the images and videos into their ascii form in python language using python pillow library and opencv image processing library.

Converting image to its ascii form:

The ASCII characters are arranged from darkest to lightest, meaning the darkest pixel will be replaced with @ and lightest with .
We need to convert the image to a smaller width and height so that it doesn’t result in too large of text size. To find the new_height, multiply new_width with height and divide by width.
We can use the convert method on the image with L option to get a GreyScale image.
To convert the image to ASCII character first, get each pixel value(0-255) and the corresponding ASCII character and join them as a string.
Now, we have a to_greyscale method to convert our image to a GreyScale image and a pixel_to_ascii method to convert our GreyScale image to ASCII string. Once we get the ASCII string of the image, we need to split the string based on the image’s width and save it in a file.


Converting video to its ascii form:

In asciify video, we will create a command line video player with Python Image Library (PIL) or pillow library and opencv .
We will first read frame of a video with open cv the change all the pixels of that frame to ascii characters and then we will display those characters on command line when we will print one  frame after another on command line it will create an illusion as if a video is playing inside the command line.

Summary of project:

In this project basically use of python libraries (openCV , pillow ) are used for image processing , sampling , scaling  and transforming images to map pixels to their desired characters and handling image aspect ratio is used.


referances/resourses:
https://www.geeksforgeeks.org/converting-image-ascii-image-python/
https://www.youtube.com/watch?v=55iwMYv8tGI
