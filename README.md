# PIKI
This is my implementation of recommendation system after reading several chapters in <a href="http://www.cs.bme.hu/nagyadat/Recommender_systems_handbook.pdf"Recommendation System Handbook</a>. This work is a prototype and is based on Pinkoi. It can retreive 6 relevant products from 200k products list in average 0.15~0.30s.  To ensure everything works smoothly, check follwoing dependencies

* Python 2.7up (it might not work for python 3)
* Apache Spark 1.5.1 up(If you want to run DesignerSimilarity.ipynb) 


Note: your should launch spark from command line by: IPYTHON_OPTS="notebook" bin/pyspark
