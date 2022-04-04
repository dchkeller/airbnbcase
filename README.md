
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The included code runs on the Anaconda distribution of Python (Python v3.x).
The main code relies on numpy, pandas and sklearn.
folium is used to create a heatmap on a geographic map.
requests is used to download datasets from inside airbnb, if you wish to do so.
datapane is used to upload plots and tables to an online report for later embedding. If you wish to make use of datapane, you need to register and generate an api-key in datapane. Create a file config.py in the root-directory and define a variable datapane_token:
	datapane_token = "your_api_token_from_datapane"

## Project Motivation<a name="motivation"></a>

For this case study, I was interested in using AirBnB data to understand:

1. What is the market offer in certain regions?
	* Where are the best rooms?
	* What kind of appartment is typically for rent?
	* What are the prices?
2. What can you tell about the reviewers?
	* How does the number of reviews develop over time?
	* Are there effects over seasons, years or day of weeks for the reviews?
	* Are reviewers revisiting or changing their favorite rooms?
3. How can you optimize your revenue on AirBnB as a host?
	* How can we model revenue?
	* How can we determine, what has an influence on the revenue?

The code is reusable. It could be used on different regions from airbnb as well.

## File Descriptions <a name="files"></a>

* There is one [notebook](airbnbcase.ipynb) available here to showcase work related to the above questions. Markdown cells were used to assist in walking through the thought process for individual steps.  
* Data is contained in a [separate directory](data). If you wish to directly download data from airbnb inside, you can empty the data directory and let the notebook download the files directly.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [on medium](https://medium.com/@david.ch.keller/38b5deec9261).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Code here is provided under the terms of the MIT-License agreement. A copy of the license is included in the LICENSE file.

Included data is provided by Airbnb through [Get the Data Page](http://insideairbnb.com/get-the-data.html) under the terms of the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/). The included datasets are provided without changes. Thanks to Airbnb for enabling this study.

