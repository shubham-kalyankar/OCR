# OCR
OCR (object character recognition) is basically used to detect text in image

tessaract developed by google can be used for this but it requires white background with black text or black background with white text. The requirement of client was to detect text from an image of embossed text which is of same color and shiny surface which is very difficult for the computer to detect.

Here, we propose of using edge detection techniques with different light angles which will enhance the edges and then use these edges to detect the text.
