# Subjective Answer Evaluation System

Python implementation for evaluating the subjective answers written by students based on model answers provided. 
 

# Dependencies

- python >= 3.5
- NLTK library
- requests==2.11.1
- numpy==1.14.0
- pandas==0.22.0

# Usage

cd path/to/Evaluation
python evaluate_poc.py model\1.txt student\st_1.txt 5
  
First argument to evaluate_poc.py is the model answer, 2nd argument is student answer and third argument is total marks to evaluate on.

# Output

Ouput will be displayed in terminal. It shows the 
- model answer entities
- matched entites & number of matched entites
- Keyword score, Grammar score, Named entity score
- Total marks obtained by student out of marks given as argument to program 