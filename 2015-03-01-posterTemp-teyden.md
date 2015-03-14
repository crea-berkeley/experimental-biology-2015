

```
___
layout: post
title: Poster Template
author: Teyden Nguyen
___
```


###1. Introduction 

######**MOTIVE**:  No clear view of aging processes. Why?
<ul>
<li>Complex subject — hard to investigate experimentally</li>
<ul>
<li>large number of interactions</li>
<li>dynamic processes</li>
	>> variant between individuals
	<br>>> variant throughout individual's lifetime
</ul>
</ul>

However, with rapid growth in increasing research data, there's a need to resolve limitations in the  human ability to read, curate, and make meaningful connections out of large data sets. 

***In the wet-lab, machine automation of mundane laboratory tasks have allowed scientists to spend more time doing actual analysis on scientific concepts, a better use of their time.***

######**PROPOSED SOLUTION**:  
>> * Automate curation process through AI system to extract knowledge from scientific text and discover patterns
>> * Assist with hypothesis generation in the life sciences by applying functions to mined data, e.g., producing visualizations to highlight anomalies in research data that may not be seen by the human eye / reader


Thus, similarly to the wet-lab, if we assign the mundane curation processes to a specially designed AI system tailored to extract knowledge on biological aging, (hopefully) scientists can spend more time doing analysis on the scientific concepts rather than reading 20+ articles of repeat studies to ensure confidence of results. 


>> *HYPOTHESIS*: INCREASE RATE OF PATTERN DISCOVERY IN DYNAMIC PROCESSES THROUGH FIELD-SPECIFIC NLP SCHEMA FOR TEXT MINING ?


###2. Background

>> * Build text mining system tailored towards biological text mining

<ul><li>All steps to-date (not listing it here) and including a portion not yet discussed but is critical to a complete system:</li>
<ul><li> >> Implement Named Entity Recognition and Classification (NERC) techniques and integrate with information retrieval system (i.e. rule-based approach requires that all biological entities can be quantitatively measured...)</li>
<li> >> Use domain knowledge from biomedical ontologies with machine learning approaches using HMM, or other models appropriate for recognizing biological objects (protein, cell-type, cell-line, etc.)</li></ul>
</ul>

>> * Apply graphing functions to map linkage between relational text (visualization)

>> * Observe relationships between data points

>> * Apply more clustering & analysis functions to further manipulate data


*In terms of our motive…*
CREA is attempting to model the concept of aging from a systems biology standpoint, looking at interactions between biological components in the body to give rise to function and behaviour of that system.

Hence, as **BIOLOGICAL AGING is a subject of growth**, which is a **function of time (i.e. X(t) …)**, as well as a **function of several additional parameters**… 
<ul>
<li>Set additional parameters to our growth function to be measures of quantifiable biological objects, *e.g. cell volume, membrane thickness, telomere length, amount of oxygen radicals, amount of accumulation of somatic mutations, concentration of p450, etc.*</li>
</ul>

**QUERY SEARCH:** Use parameters, biological objects, and combinations of biological objects paired with common verbs describing biological events as search queries for PubMed; extract all relations from abstracts containing search query. Sample sets of query searches:

<ol>
<li>parameters = [“cell volume”, “membrane thickness”, “telomere length”, “concentration of X”, “density of Y"]</li>
<li>biol_objects = [“p450”, “astrocyte”, “dopamine”, “hypothalamus”, “glucose”, “insulin”, “somatostatin”]</li>
<li>objectsNverbs = [[“p450”, “increase”], [“p450”, “decrease”], [“dopamine”, “activate”], [“insulin”, “inhibit”], [“somatostatin”, “excite”]]</li>
</ol>


###3. Materials & Methods

>> 1. Construct NLP system to gather information from unstructured text
>> 2. Extract knowledge from retrieved information; abstract relational data
>> 3. Relational database

<ul> 
<li>Allows us to publish data</li>
<li>Provides opportunity for usage of data</li>
</ul>
>> 4. Produce and perform functions on data

<ul><li>Visualization --> GUI</li>
>> Allow people to see what is being done
<li>Web application --> UX</li>
>> Allow interaction with what they see</ul>


###4. Discussion
* Tie together everything we’ve done
* Is it consistent with our motive? 
* Does it benefit the research & open-source community? 
* *...?*


###5. Conclusion
* Were our goals met? 
* What could we improve with? 
* What are we planning for next?
* *...?*
