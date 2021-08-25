# DeCore Idea: deep learning meets interior design
Louisa Reilly

## Background:
HGTV has recruited you to create an image classifier that can discern the various common interior design styles. They have plans to use your model for a prototype recommendation engine that can give designer's clientele and their viewers recommendations on what other pieces would match their own decorations and furniture. 

## Design:
A classification model will be built using a residual network (ResNet). The model will be able to classify various furniture/ decor images into a variety of design styles. Once that is working sufficiently, I plan to build a recommendation engine that will take in a picture of a furniture piece or decoration and return suggestions that will match said item.

## Data:
Pretrained weights from the [LSUN: Construction of a Large-scale Image Dataset using Deep Learning with Humans in the Loop](https://www.yf.io/p/lsun) will be used for transfer learning.

Pinterest images obtained via webscraping with an unofficial Pinterest Image Scraper. The images are of nicely decorated interiors in the following design styles:
- **Modern**
![Modern Style](images/modern_eg.jpeg)

- **Transitional**
![Transitional Style](images/transitional_eg.jpeg)

- **Traditional**
![Traditional Style](images/traditional_eg.jpeg)

- **Mid Century Modern**
![Mid Century Modern Style](images/mid_century_modern_eg.jpeg)

- **Rustic**
![Farmhouse Style](images/farmhouse_eg.jpeg)

- **Industrial**
![Industrial Style](images/industrial_eg.jpeg)

- **French Country**
![French Country Style](images/french_country_eg.jpeg)

- **Scandinavian**
![Scandinavian Style](images/scandinavian_eg.jpeg)

- **Art Deco**
![Art Deco Style](images/art_deco_eg.jpeg)

- **Eclectic**
![Eclectic Style](images/ecclectic_eg.jpeg)

- **Shabby Chic**
![Shabby Chic Style](images/shabby_chic_eg.jpeg)

- **Bohemian**
![Bohemian Style](images/bohemian_eg.jpeg)

## Tools:
- Pinterest Image Scraper without the offical API from [iamatulsingh's github](https://github.com/iamatulsingh/pinterest-image-scrap)
- Image processing library OpenCV
- Visualization with Tableau and Matplotlib
- Recommendation Engine Surprise
- Neural Network Implementation: Keras
- 
## MVP:
A functioning convolutional neural network that can discern different design styles based on an image of a piece of furniture.