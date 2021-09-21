<p align="center">
  <a href="https://www.perceptilabs.com">
  <img src="./pl_logo.png">
  </a>
</p>

# Blood detection in darkfield microscopy images

This dataset<sup>1</sup> contains over 366 darkfield microscopy images.

The data can be used to build and train an ML model that can segment blood cells.

# Structure

This repo contains the following structure:

- **images**: contains the images directory.
- **masks**: contains the masks directory.
- **dataset.csv**: CSV file with all required data.

<p align="center">
  <img src="./sample.png">
</p>

The following shows a partial example of the data stored in **dataset.csv** that is used as the main example.

| **images**  | **masks** |
|-------------|----------------------------------------|
| images/001.png | masks/001.png |
| images/002.png | masks/002.png |
| images/003.png | masks/003.png |
| images/004.png | masks/004.png |
| images/005.png | masks/005.png |
| images/006.png | masks/006.png |
| images/007.png | masks/007.png |
| images/008.png | masks/008.png |


# Community

Got questions, feedback, or want to join a community of machine learning practitioners working with exciting tools and projects? Check out our [Community](https://forum.perceptilabs.com/)!

<sup>1</sup> Dataset Credits: https://www.kaggle.com/paultimothymooney/blood-cells

