# Location-Entity-Recognition

Jupyter Notebook (Python 3) guiding researchers through identifying location entities within text.

Specify the name/path of a txt file. This notebook will use spaCy's NLP entity recognition to automatically identify locations. Outputs include in-line text with recognized entities highlighted, a map visualization of proportional circles with the radius of each circle representing the frequency of the location in the text, a word cloud of the recognized locations, and a column chart of the top locations.

Make sure the text file is saved as ASCII or ANSI as UTF and Unicode may contain characters causing spaCy's NLP processor to crash.

The NLP Entity Recognition using spaCy (https://spacy.io/) is based on this Towards Data Science blog post: https://towardsdatascience.com/named-entity-recognition-with-nltk-and-spacy-8c4a7d88e7da

Resulting interactive map visualization uses the Bing Maps geocoding API (http://www.bingmapsportal.com/) via the Geocoder library (https://geocoder.readthedocs.io/index.html). *It is necessary to register for a freely available BING Maps Key to create the map visualization.*

Resulting wordcloud visualization uses amueller's word cloud generator (https://github.com/amueller/word_cloud).

Resulting bar chart visualization uses the standard matplotlib library (https://matplotlib.org/).
