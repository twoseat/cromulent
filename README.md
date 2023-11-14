__This is a test of options for sharing resources for countries implementing ICD-11. It will definitely go away in a few days, and its content only works on my machine for now, so you really don't want to use it!__

# Instructions for use
This repository has 2 sections:

## Data
Individual files that are combined to create a dictionary. You can use these files individually by importing them into an Access (or other) database, editing them as you need. Or you can use the Python script to build a dictionary for you (currently only in Access)...

## Src
Python code to build a dictionary in Access using all the supplied files.
* This is destructive - it deletes most of the data in your dictionary before importing the files, so be careful!
* All the files supplied need to be available, otherwise you'll have an incomplete dictionary
* The target database must be closed before running, otherwise bad things happen
* Run using `python build.py <name and location of database>`

# Contributions
If you find a code or standardisation that you believe is wrong please log an issue. Note that:
* The issue must be universal - we won't change a code just to suit the way your country handles a particular condition
* We generally won't add new terms or standardisations. Different countries see different terms, this dictionary will only contain terms that _we_ see

If you don't like these terms you should consider forking this repository and customising it to suit your needs.
