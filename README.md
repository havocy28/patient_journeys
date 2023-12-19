# Patient Journey Clustering

## Overview
This repository contains code for creating patient journey clusters based on cases represented by string sequences. Each character in the string corresponds to a specific event or action in a clinical document, encoded by True/False values. Time gaps between events are also represented in these sequences: a gap of more than 24 hours but less than 72 hours is indicated by an 'x', and a gap of more than 72 hours is indicated by 'xx'.

## Mappings
The character mappings in the sequences are as follows:

- `"a"`: consult with nothing noted
- `"b"`: hospitalization
- `"c"`: given a new antibiotic
- `"d"`: given a new antibiotic and hospitalized
- `"e"`: surgical intervention performed
- `"f"`: surgical intervention performed with hospitalization
- `"g"`: surgical intervention performed with new antibiotic given
- `"h"`: surgical intervention performed with new antibiotic given with hospitalization
- `"i"`: abscess was noted draining on exam
- `"j"`: abscess was noted draining on exam and patient hospitalized
- `"k"`: abscess was noted draining on exam and new antibiotic given
- `"l"`: abscess was noted draining on exam, a new antibiotic given, and patient was hospitalized
- `"m"`: abscess was noted draining on exam and surgical intervention was performed
- `"n"`: abscess was noted draining on exam, surgical intervention was performed, and patient was hospitalized
- `"o"`: abscess was noted draining on exam, surgical intervention was performed, and new antibiotic was given
- `"p"`: abscess was noted draining on exam, surgical intervention was performed, a new antibiotic was given, and patient was hospitalized
- `"x"`: time gap

## Instructions for Use
To use the code in this repository:

1. Refer to the `Patient_Journey_Clustering.ipynb` notebook for an example of how to use the code.
2. Ensure that all required libraries listed in `requirements.txt` are installed.

## Citation
When referencing the use of this code, please cite the following paper:

{Citation Pending Official Publication}
