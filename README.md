# Data test

In this repo, I will provide a notebook that analyzes data and attempst at providing recommendations to improve a service. This is mainly to test my analytical and improvement capabilities.

## Tools used

The file is a Jupyter notebook using Python3. I tried to use a number of libraries that may help me understand the data in a better way.

### Python libraries

* __NumPy__: for matrices use, especially coming in handy for the other libraries
* __Pandas__: used for importing the *data.csv* file, putting it in *DataFrame* format to be used later in a proper, easy and practical way
* __Matplotlib__: used to visualize the data in a structured manner

#### Note

Due to the nature of the data provided, I couldn't have engineered numerical features (which would have been richer in information and would have allowed me to use other tools such as __Scikit-Learn__ or any other visualization means that could give birth to new perspectives regarding the data). If you find any way to create any new features, do not hesitate to tell me.

## Observations

All visuals created from the dataset are shown inside the notebook. Feel free to check them as well as the comments provided to explain/describe/understand them.

## Recommendations

The recommendations we would like to provide are the following, ordered from least to most important, according to our reasoning (you may also find them at the end of the notebook):

* Check if there is a problem with *Stream n°2* when it comes to the *Olga* browser
* Improve the compatibility of the streaming with three browsers essentially in this order:
    * EarthWolf
    * Iron
    * Swamp

This order may be different than what the access ratio may infer, but it is mainly due to each browser's popularity, with *EarthWolf* being the most popular, and *Iron* being the second most popular. This ensures that more people will accede to the stream content.

* Improving service compatibility with the *Fro* and *Datch Telecam*, in this same order, for reasons of popularity among users (even if the technical issue is more remarkable with *Datch Telecam*).
