# Sub-Event-Detection
A binary classification problem where the goal is to build a model that can accurately predict the occurrence of notable events within specified one-minute intervals of a football match.

The final model was trained on a Twitter dataset centered on the 2010 and 2014 FIFA World Cup tournaments.  Each period is annotated with a binary label: 0 if no notable event occurred, or 1 if a significant event—such as a goal, half time, kick-off, full time, penalty, red card, yellow card, or own goal—occurred within that period. 

The complete methodology (from data preprocessing to model selection, including feature engineering) used to address this challenge is documented in the REPORT file and supported by the corresponding scripts provided in the attached notebook.

## Notebook
All the scripts are consolidated into a single, fully commented Jupyter notebook that follows the chronological order of the report for clarity and ease of use. All the cells have to be run sequentially. 

The notebook is designed for Python 3.8 or later. All the required packages are imported in the first cell. Make sure they are installed and updated.
