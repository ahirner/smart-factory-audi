# Preparation
## What do we know about data science for automotive manufacturing?
1. Mihai Pelko [presented](https://www.eventbrite.com/e/munich-meetup-deep-dive-into-tensorflow-tickets-26422317864) how [Norcom](http://www.norcom.de/en) identified **anomalies in gear-shifting** data
 * ![Norcom intro](https://raw.githubusercontent.com/ahirner/smart-factory-audi/master/aux-info/norcom.jpg)
 * Mainly transforming fixed-length snippets of vibration data into pictures and training a CNN to classify
2. A Bosch SI [webinar](https://www.bosch-si.com/contact-forms/manufacturing-analytics/download-page.html) provided **three examples** of data-driven improvements in manufacturing:
 * Test time reduction, scrap reduction (correlating most important features from process data that lead to scrappage of parts), packaging standardization
 * ![screenshot Bosch SI](https://raw.githubusercontent.com/ahirner/smart-factory-audi/master/aux-info/bosch-si.png)
 * General goal: utilize event patterns and find out root causes
3. Volkswagen's Daniel Leimer explained how deep learning leap frogs classical approaches for **visual defect detection** at [Munich's Datageek Day](http://munich-datageeks.de/dadada/)
 * slides to be received
4. Bosch Kaggle challenge: [**Reduce manufacturing failures**](https://www.kaggle.com/c/bosch-production-line-performance)

## Quick data exploration & vizualation tools
1. [Caravel](https://github.com/airbnb/caravel) is a data exploration platform designed to be visual, intuitive, and interactive
2. ...

## Machine Learning Tidbits
* How to write [idiomatic Pandas](http://tomaugspurger.github.io/modern-5-tidy.html) (for data cleaning)
* How to use [scikit-learn by example](https://github.com/jakevdp/PythonDataScienceHandbook) (great notebooks)
* ![pic](https://raw.githubusercontent.com/ahirner/smart-factory-audi/master/aux-info/Vanderplas_Python_Stack.png)[Python Data-Science Stack](https://speakerdeck.com/jakevdp/pythons-data-science-stack-jsm-2016)
* ![Nautil Article](http://static.nautil.us/10301_b1f130b49d0fcfa2348098ee4467452f.png)...Trade-off between interpretabilty and accuracy
