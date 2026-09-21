# GroupDNA — WhatsApp Group Analytics

GroupDNA is a Python-based WhatsApp group analysis project that extracts communication patterns, word statistics, activity patterns, response behaviour and personality archetypes from a WhatsApp group chat.

## Project Features

- WhatsApp chat parsing
- Group overview and message statistics
- Word-frequency analysis
- NumPy-based 24-hour activity heatmap
- Response-time analysis
- Silent-streak analysis
- Personality archetype system
- Final formatted GroupDNA report

## Technologies Used

- Python
- NumPy
- File handling
- datetime

## Project Constraints

The project was implemented using Python fundamentals and NumPy.

The following libraries and techniques were not used:

- pandas
- matplotlib
- seaborn
- plotly
- regular expressions
- collections.Counter
- collections.defaultdict
- WhatsApp analyzer libraries
- Machine Learning libraries
- NLP libraries

## Dataset

The project uses the provided `hostel_bois.txt` dataset.

The notebook also contains an analysis of a personal WhatsApp group chat for project experimentation. The personal chat file itself has not been uploaded to this public repository.

## How to Run

1. Download or open the GroupDNA notebook.
2. Open the notebook in Google Colab.
3. Upload `hostel_bois.txt` when prompted.
4. Run the notebook from the first cell to the last cell.
5. Review the generated GroupDNA report.

## Main Outputs

The notebook generates:

- Total message count
- Message count per participant
- Top group words
- 24-hour activity heatmap
- Average response times
- Silent streaks
- Personality archetypes
- Final GroupDNA report

## Personality Archetypes

The project identifies six personality archetypes using rule-based analysis:

- SPAMMER
- GROUP MOM
- NIGHT OWL
- STORYTELLER
- DRAMA QUEEN
- GHOST

## Final Report

The final report combines group activity, vocabulary, response patterns, silent streaks and personality archetypes into a formatted text-based report.

## AI Assistance

AI tools were used as a learning aid for understanding selected Python concepts and debugging. AI-assisted sections are identified using comments in the notebook where applicable.
