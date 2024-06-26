# Elements-of-AI

<!-- This is the markdown template for the final project of the Building AI course,
created by Reaktor Innovations and University of Helsinki.
Copy the template, paste it to your GitHub README and edit! -->

# Optimization at an Oil Refinery

###### Building AI course project

## Summary

Oil refineries are complex systems that require optimization to maximize efficiency and minimize costs. AI can be used to optimize the operation of oil refineries by predicting the quality of the final products based on the input crude oil and adjusting the process parameters accordingly. It can also be used to predict equipment failures and schedule maintenance to prevent unplanned shutdown.

## Background

4th industrial revolution is going to connect all machinery in a production plant, so engineers can analyse, optimize and ensure quality of the product. Data collected from Supervisory Control And Data Acquisition (SCADA) can help predict failures which are usually infrequent, aiding in Predictive Maintenance by data-driven decision-making, thus significantly reducing costs.

## How is it used?

The sensor data, if abnormal in a pattern distinct from that not due to hardware issues can be used to predict equipment failures, much more efficiently than with manual observation of such abnormality, either by indicator reading or hardware inspection. This failure, although uncommon, can occur at any time. Managing such technical data will require engineers who could read between the lines of sensor data. Engineers with AI skills would be required to work on software which can handle data provided by sensors in components of the oil refinery, in various equipment around the facility.

<img src="https://imechewebresources.blob.core.windows.net/imeche-web-content/images/default-source/oscar/institution-news/ai-in-2-800.png?sfvrsn=d429412_2" width="1000">

## Data sources and AI methods

The data will come from the instrumentation and sensors installed on various equipment, which is primarily sent to control rooms.

Pattern recognition methods such as statistical analysis and k-NN can be used. The software would need to be trained on historical data to learn the relationships between the input and output variables. This model built on training data can then be used to predict the failure of equipment based on the current, testing data from sensors.

## Challenges

The instrumentation used is usually traditional, analog needle indicators, which will need to be replaced with digital sensors. Most workers at a typical refinery in Pakistan are not well-versed in technical computer usage, or in AI, so they would need to be trained to use the software. The software would also need to be user-friendly and intuitive to use. The software would also need to be secure to prevent any unauthorized access to the data.

## What next?

The software could also be expanded to include and collaborate with more refineries, which would require more data and more computational power.

## Acknowledgments

- Reaktor and University of Helsinki for [Elements of AI](https://www.elementsofai.com/): [Introduction to AI](https://course.elementsofai.com/) and [Building AI](https://buildingai.elementsofai.com/) courses

- IMechE: Institute of Mechanical Engineers - [Why mechanical engineers should learn A.I.](https://www.imeche.org/news/news-article/why-mechanical-engineers-should-learn-a.i)
