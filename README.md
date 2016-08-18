# Crop yield exercise
Author: Alek Petty / www.alekpetty.com / @alekpetty

The model is contained in the IPython Notebook, complete with description and discussion. See below for a repeat of the general approach taken...

To run the Notebook you may need to install a few extra Python libraries (all available using conda). E.g. seaborn for data viz and scikit-learn for the random forest model.

# Approach
Use Python Pandas to read in and manipulate the two datasets provided   
Use matplotlib to map/visualize the data   
Run some simple statistics (linear regression) to check there is no simple solution (e.g. a variable that stands out for being a good predictor)   
Finally we use a Random Forest implmentation in scikit-learn to try out and evaluate a more complex prediction framework   

Issues: It would have been nice to have more years of data to play with. It looks like the yields are very regional, and this is what dominates the signal (lat/lon, not the county etc). I've experimented with removing this information to try and understand if we can use just the atmospheric data to predict yields, independant of location, but the skill decreases markedly.
