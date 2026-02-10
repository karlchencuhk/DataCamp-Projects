# Mark down what I learnt from this exercise
## import os os.chdir("/Users/kahouchen/Downloads/Learning Data/DataCamp/Calorie")
  
File and Directory Operations:

os.getcwd(): Get the current working directory.

os.chdir(path): Change the current working directory.

os.mkdir(path): Create a new directory.

os.makedirs(path): Create directories recursively (creates intermediate directories if they are missing).

os.rmdir(path): Remove (delete) a directory.

os.listdir(path): List the contents of a directory.

os.remove(path): Delete a file.

os.rename(src, dst): Rename a file or directory.

os.path.join(path1, path2, ...): Join path components into a single path using the correct separator (/ or \) for the current operating system.

## with open('nutrition.json', 'r') as json_file:

open(...)Built-in function to open a file

'nutrition.json'The name of the file we want to read

'r'read mode → we only want to read, not write or modify the file

with ... as json_file"Open the file and give it the temporary name json_file. 

## nutrition_dict = json.load(json_file)  # Load the JSON content into a dictionary

reads the JSON file and automatically converts it into normal Python dictionaries

## list(nutrition_dict.items())[:3]

shows you the first 3 key-value pairs from the dictionary nutrition_dict





