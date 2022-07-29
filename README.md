# TensorFlow-multiples-dataset

![Esta es una imagen](https://torres.ai/wp-content/uploads/2019/09/tf_logo.png)

COURSE PROJECT (Main Project)
MNIST (American Sign Language) Sign Language Description
This dataset was adopted from the MNIST sign language, converting the CSV file into images and also decreasing the overall size of the database.

There are a total of 27,455 greyscale images of size 28 * 28 pixels ranging in value from 0-255. Each case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9 = J or 25 = Z due to gestural movements).

The data is stored in an orderly fashion and is compatible for use with dataflow generators in the TensorFlow API. Each folder is named according to the kind of images stored inside, which makes it easy to load and view.

The images are stored in 'JPEG' file format.

The original hand gesture image data represented several users repeating the gesture with different backgrounds. The MNIST sign language data came from a large spread of the small number (1704) of colour images included as uncropped around the hand region of interest.

To create new data, an ImageMagick-based image pipeline was used and included cropping to just hands, greyscaling, resizing and then creating at least 50+ variations to increase the number. The modification and expansion strategy was filters ('Mitchell', 'Robidoux', 'Catrom', 'Spline', 'Hermite'), along with 5% random pixelation, +/- 15% brightness/contrast and finally 3 degrees of rotation. Due to the small size of the images, these modifications effectively alter the resolution and class separation in interesting and controllable ways.

Source: TecPerson - Kaggle
