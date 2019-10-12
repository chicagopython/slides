# September 2019 Data SIG

[Property Testing Pandas with Bulwark](zax-rosenberg--property-testing-pandas-with-bulwark.pdf)
by Zax Rosenberg

While testing has long been shown to reduce bugs and lower development costs, tests are sorely lacking in much of the data science world. Some of the reasons for this lack of tests are that data scientists/analysts often don't have the time, knowledge, or even exact data to write useful tests. Property testing, which involves checking that an object has certain properties, can allow us to still write tests even under such circumstances.

Since a lot of data work is done in Python, and Pandas is one of the go-to libraries for analyzing tabular data in Python, wouldn't it be nice to be able to add property tests to our DataFrames while we code? Enter Bulwark - a pip-installable property testing library for Pandas DataFrames that makes it easy to check that your data meets your assumptions of what it should look like at any (and every) step in your code, without making you work too hard.

This talk is for anyone who works with data in Python, and no prior testing experience is required. It will expand the definition of property testing, why it's useful, and demonstrate multiple examples of how to easily add property tests to code with Bulwark.

Speaker Bio:

Zax is currently a Senior Data Scientist at SPINS, where he develops data-driven analytic solutions for grocery retailers and CPG companies. He is also the Director of ChiPy‘s (Chicago Python User Group’s) mentorship program, co-host of ChiPy’s Project Night, and an avid tech enthusiast/blogger.

---

[Risk Weighting: The Best Thing Since One Hot Encoding!](laurel-ruhlen--risk-weighting.pdf)
by Laurel Ruhlen

One Hot Encoding (OHE) is a common method for turning categorical variables into numbers. But what if there were a better way? This talk introduces a risk-weighting technique for wrangling categorical variables into submission. Also included: sklearn pipeline compatible risk weight transformer!

Speaker Bio:

Laurel Ruhlen is a data scientist at Braintree. She is a recovering physicist and a pool noodle enthusiast.

---

[Facade Pattern](aly-sivji--facade-pattern.pdf)
by Aly Sivji

Developers spend lots of time writing code to integrate third-party packages and APIs into our project. We spend additional time updating systems when our dependencies change. This talk will demonstrate HOWTO leverage the Facade Pattern to hide complexity and isolate the impact of changes.

Speaker Bio:

Aly Sivji is a Canadian expat living in Chicago. By day, he builds backend systems at Numerator. By night, he is a co-organizer of the Chicago Python Users Group (ChiPy). Aly is an active participant the ChiPy Mentorship Program and he loves helping intermediate developers become experts. Outside of Python, Aly enjoys cycling, reading, and rewatching old TV shows.
