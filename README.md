# Working with Documents
Scripts and resources for working with documents

For now, these are stored in jupyter notebooks

# 🍱 - Scripts

## Operations on files
*It would be a good idea to fit all of this functionality into a single file*

1. **get_txt.ipynb** - retrieves text to txt file using `docx2txt` 🏭
2. **get_text_to_df.ipynb** - retrieves text from a docx file to a `pandas` dataframe using `docx2txt
3. **find_duplicates.ipynb** - find duplicate files between two folders. Choose what to do with them.
4. **file_present.ipynb** - given a list of `filenames` and a folder, find which ones are missing from the folder.
5. **doc2docx.ipynb** - change format of a `doc` file to a `docx` one
6. **unpack.py** - script for unpacking multiple zips from a folder


## Operations on raw text

1. **IsInTxt.ipynb** - creates columns based on occurences of words  
parameters: `phrases, column_names, is_regex` 🏭

2. **GetMergeFields.ipynb** - retrieves merge fields using `doc2txt` library for text extraction and `re` for retrival


## NLP Tasks

1. **TopicModeling.ipynb** - topic modeling task solved based on `BERTopic` library. 
Provides you with topics and topic probabilities. 🏭
