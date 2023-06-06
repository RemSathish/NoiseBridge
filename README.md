# NoiseBridge
NOISEBRIDGE - HACKER/MAKER SPACE (NLP PROJECT)

Project Objective: 
To find the evolution of NoiseBridge from the historical events of Meeting Notes which are conducted weekly at the space. 

•	Scraped all the meeting notes (in HTML format) from 2007 till first week of April 2023 using a python code in Google Colab.
•	A Python package called ‘Beautifulsoup’ was used for parsing HTML documents.
•	All the text for Meeting Notes, Discussion Items and Excellence in the header, list, underline, and paragraph tags were extracted and appended to a text list.
•	Words in each line of text list were cleaned and added to a dictionary of notes.
•	Applied the Text2Emotion package to the dictionary of notes that pulled 5 basic emotions (Happy, Angry, Sad, Surprise, and Fear)
•	The sentiment data was exported into a CSV file and performed some visualizations using viz packages matplotlib and seaborn. 
