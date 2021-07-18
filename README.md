# Ranking Of Extracted Interests From User Generated Texts In Social Media Using Semantic Graphs
The selection of the most descriptive terms or passages from user defined texts is crucial for several tasks, such as feature extraction and summarisation. 

For instance, if a social media message is about the service quality of the bus transportation mode - "My bus is delayed." - then the responsible entities should have the necessary tools and information to tackle the existent problem. However, to extract the knowledge to handle the solving task, first it is necessary to filter travel-related messages from the non-related and only then explore the topic, sentiment, or even the target of its content. 

In the majority of the cases, research works propose the ranking of all candidate keywords or sentences and then select the top-ranked items as features, or as a text summary respectively. The selected terms indicate the user's area of interests.  In this project I present SemanticRank, a graph-based ranking algorithm for keywords and sentence extraction from text.  More specifically, SemanticRank capitalises on the creation of term and sentence graphs from texts.

## Importing the required Open Source Tools
-->spaCy is an open-source software library used for natural language processing.

-->Pandas is used for data manipulation and is basically a data analysis toolkit.

-->NetworkX here is used to draw a semantic graph.

-->matplotlib.pyplot is a collection of command style functions that make matplotlib work like MATLAB. Each pyplot function makes some change to a figure: e.g., creates a figure, creates a plotting area in a figure, plots some lines in a plotting area, decorates the plot with labels, etc.

-->nlp(natural language processing) is an object assigned to spacy.load(en_core_web_sm).

-->The model (en_core_web_lg) is the largest English model of spaCy with size 788 MB. There are smaller models in English and some other models for other languages (English, German, French, Spanish, Portuguese, Italian, Dutch, Greek).  en_core_web_sm is a smaller version of it.

## Output
At the end of Semantic ranking, I have generated a list of top semantic ranked words which shows the ranking of people’s interests from generated texts in social media. In the above given example people are more interested in domains like 'corona virus', 'Navaratri Goddess' and so on. 

##  
This project was made as a mini-project for the course CS6109 - Compiler Design

For docs and info contact sobikasenthilnathan@gmail.com
