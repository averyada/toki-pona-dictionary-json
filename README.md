# Toki Pona JSON Dictionary

This is a conversion of the Toki Pona Official Dictionary to JSON. Due to the
formatting of the Toki Pona PDF, it was first hand-converted to two .txt files.

The script `load_dictionary.rb` will parse these two text files and generate two
JSON files, `toki-dictionary.json` and `toki-partsofspeech.json`.

There is no need to run this script unless you're changing the values in the 
dictionary or parts of speech text files. The generated JSON files have been
added to version control and are available in the root of this project. Simply
download them from Github through the web UI if you are an application developer
and want to use them in your own projects.