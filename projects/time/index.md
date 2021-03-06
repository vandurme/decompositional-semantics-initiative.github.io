---
layout: project
handle: time
search_omit: true
---

Finding temporal relations between events in textual description is an important problem in natural language processing as it aims to facilitate understanding beyond surface representation for downstream tasks such as Question Answering, Information Extraction, Summarization etc. Traditionally, it involves classifying a given event-event pair to a set of predefined classes such as "before", "after", "simultaneous" etc. 

In this line of work, we develop a new temporal-relation annotation that maps every event to a timeline represented in real numbers. In addition to that, we also develop duration annotations for every event represented in the form of 11 classes. The aim is to capture a fine-grained temporal-relation jointly modeled with duration to help model the relations better. These annotations could also be mapped to the traditional classification problem such as the Timebank Corpus (Pustejovsky et al., 2003) without much effort.
