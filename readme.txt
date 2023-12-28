The following libraries have to be installed for executing the python scripts

pip install wordcloud
pip install textblob
pip install selenium

Other data analytics libraries 
pip isntall pandas,numpy,matplotlib


'play_store_reviews_extractor.ipynb' has an infinite while loop in the 'scroll_down' function. The browser 
has to be monitored regularly to check if the driver has reached the end of the play store review pane. Upon scrolling to the end the kernel has to be interrupted.