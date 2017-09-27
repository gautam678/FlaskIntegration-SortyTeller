# FlaskIntegration-SortyTeller

Sorting images in an album is an interesting task in computer vision and machine learning. It allows us to build systems that can generalize and exploit the temporal relationship between images. We propose an approach to this problem taking into account and using a latent representation of the input (shuffled) sequence, which uses Pointer Network (ptrNet) to utilize the whole contextual information to perform story ordering/sorting. We display the effectiveness of this model through various experiments.

The report to this project can be found here: [Full report](http://www.cs.virginia.edu/~gs9ed/reports/VislangProjectReport.pdf)

## Requirements
* Flask
* Flask_bootstrap
* tensorflow
* Keras

## Implementation

 We have used the [VIST dataset](http://visionandlanguage.net/VIST/) to train our images. 
 
The implementation for this project is two-fold:
- The backend code for pointer networks can be found [here] (https://github.com/maximus009/StorySorter) . 
- The code for the webUI is in this repository.

## Serving the appliation in Flask

```
cd sortyteller
python app.py
```

Contact [me](http://www.cs.virginia.edu/~gs9ed/) for the simplified data model used in this project.
