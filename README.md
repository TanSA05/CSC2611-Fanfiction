# CSC2611-Fanfiction Final Project

## Directory Structure
* src
	* graph
		* Python code for graph, edge, node construction and analysis
	* text_preprocessing
		* Python code for pre-processing raw story data
	* third_party
		* Python third_party libraries
* data
	- raw_text: Raw story data that needs to be added
	- book_by_chapter: Story split by chapter
	- coref_rules: Coreference rules module for matching
	- entity_list: Contains the output of text processing as pickle file (ie: the occurence list)
	- graph: Narrative graph
	- results: Result plots
* models
	* Stores the weight of BERT-NER model

## Files in this Repository
* main.py: Main Python code for running the entire pipeline
* requirements.txt: Requirements.txt with all requirements for running this code 
* Raw Data with Fanfiction Stories.zip: Zipfile containing raw data
* Fanfic_code.ipynb: Main Python code for comprehensive entire corpus analysis for all original books and all fanfiction documents
* Project Results.zip: Folder containing all project results (including terminal dumps) for all code runs


This project and code has been adapted from various sources [[1](https://github.com/booknlp/booknlp), [2](https://github.com/dldk-gael/novel_story_building)] 
