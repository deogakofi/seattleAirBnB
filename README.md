2016 SEATTLE AIRBNB REVIEW
-----------------------
Review the data from AirBnB for Seattle in 2016, predict the price of listings based on descriptive and non descriptive features in dataset and explore some questions related to the dataset like:
* Do super host Get higher reviews?
* Is there a good time to book?
* What do the review comments say about Seattle?
* Is there correlation between number of available listings and number of reviews?
* Which neighbourhoods cost more?

Installation
----------------------

### Download the data

* Clone this repo to your computer.
* Code is the `AirBnb_Seattle.ipynb` file.
* Dataset is contained in the Data folder
* Data folder contains three datasets
    * `Listings`: Listing dataset of the host Listings in 2016 for AirBnb_Seattle
    * `Reviews`: Reviews dataset of the customer Reviews in 2016 for AirBnb_Seattle
    * `Calendar`: Calender dataset showing prices of listings thorugh the year for AirBnb_Seattle
* It is recommended you run the solution on jupyter notebook.


### Install the requirements

* Install the requirements using `pip install -r requirements.txt`.
    * Make sure you use Python 3.
    * You may want to use a virtual environment for this.

Usage
-----------------------

* Run Script using ipynb compiler.

Results
-----------------------
Some notable mentions discovered from the analysis include:
  * Superhosts on average got higher review scores than non Superhosts
  * Cheapest month to  book a stay on AirBnB in Seattle for 2016 was January and the most expensive was July
  * It cost an average of $23.38 more to book a stay in Seattle for Q3 2016 than Q1 which is the most expensive and least expensive quaters respectively
  * On average it was more expensive to book a stay in Seattle for 2016 on a weekend(Friday, Saturday) than weekday
  * From running a wordcloud: Great, clean and accommodate stands out in the review comments
  * There is a lot of automated review comments about cancellation on same day by host
  * There is weak positive correlation between the number of available listings and the number of reviews left on the site
  * On average, the top 5 most expenisve neighbourhoods to book a stay in Seattle for 2016 in order are Southeast Magnolia, Portage Bay, Westlake, West Queen Anne, Montlake
  * On average, the bottom 5 most expensive neighbourhoods to book a stay in Seattle for 2016 in order are Rainier Beach, Olympic Hills, South Delridge, Georgetown, North Delridge
  * Predicting the price of AirBnB listings in Seattle for 2016 using the listings dataset resulted in a rsquared score of 0.566 on train and 0.58 on the test

Extending this
-------------------------

If you want to extend this work, here are a few places to start:

* Convert `ammenties` in `listings` dataset to dummmy data and include in the linear model as a predictive variable
* Create methods for some of the cells with multiple lines of codes
* Explore predicting review related columns in `listings`
* Explore predicting price from calender dataset using time series analysis
* Combine dataset with more data from previous and subsequent years from AirBnb_Seattle to perform more detailed analysis


## Credits

Lead Developer - Deoga Kofi


## License

The MIT License (MIT)

Copyright (c) 2015 Deoga Kofi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
