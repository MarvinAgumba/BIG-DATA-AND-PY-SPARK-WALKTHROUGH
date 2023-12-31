# BIG DATA OVERVIEW

***Big data is high-volume, high-velocity, and/or high-variety information assets that demand cost-effective, innovative forms of information processing that enable enhanced insight, decision-making, and process automation.***

## The 3 V's of Big Data

![image](https://github.com/MarvinAgumba/BIG-DATA-AND-PY-SPARK-WALKTHROUGH/assets/122484885/647317b6-0fcc-4287-88d2-801e24263454)

## VOLUME - **amount of data** generated through websites, portals, and online applications in a data-driven business

![image](https://github.com/MarvinAgumba/BIG-DATA-AND-PY-SPARK-WALKTHROUGH/assets/122484885/1fb35e24-a90b-494e-b990-a524ee79ed7f)

## VELOCITY - the speed with which data is generated, and as internet speeds have increased and the number of users has increased, the velocity has also increased substantially

![image](https://github.com/MarvinAgumba/BIG-DATA-AND-PY-SPARK-WALKTHROUGH/assets/122484885/29e4dc92-5559-4472-b0d2-56899661cbaf)

## VARIETY - the structured and unstructured data that has the possibility of getting generated either by humans or by machines

![image](https://github.com/MarvinAgumba/BIG-DATA-AND-PY-SPARK-WALKTHROUGH/assets/122484885/2fa3db29-dd5f-480c-88f6-e13964b22b20)

## Big Data Analytics Tools

![image](https://github.com/MarvinAgumba/BIG-DATA-AND-PY-SPARK-WALKTHROUGH/assets/122484885/9f162189-c656-4519-903d-d34264f94312)

## Example Business Applications of Big Data Analytics

 - **Social media analytics** is based on developing and evaluating informatics frameworks and tools in order to collect, monitor, summarize, analyze, as well as visualize social media data.
 
 - **Sentiment Analysis** focuses on analyzing and understanding emotions from subjective text patterns and is enabled through text mining. It identifies the opinions and attitudes of individuals towards certain topics, and it is useful in classifying viewpoints as positive or negative.
 
 - **Recommendation Systems** Powerful recommendation engines can be built for anything from movies and videos to music, books, and products as offered by Netflix, Pandora, or Amazon.

## Installing Spark without a Docker container

Run below commands to ensure that each step works as expected:
- conda activate base
- conda create --name spark-env python=3.8
- conda activate spark-env
- conda install -c conda-forge openjdk=11
- pip install pyspark==3
- conda install -c conda-forge notebook
- python -m ipykernel install --user --name spark-env --display-name "Python (spark-env)"
- conda install matplotlib
- jupyter notebook

**Machine Learning on the scale of big data can be done with Spark using the `ml` library**
