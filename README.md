# Urdu-Speech-to-Text-Recognition-in-Recipe-Domain_NLP

The project focuses on Speech-to-text Recognition of Urdu audio recipes followed by identification of food entities such as ingredient name, quantity, unit from the generated audio transcriptions. This project was developed as a part of the course Natural Language Processing.
All the source code is maintained in the code folder.
The `Speech2text-models.ipynb` file generates the audio transcriptions from the two publicly available fine-tuned Urdu models on Hugging Face and saves the output in `Speech2Textpredictions.csv`.
The `Urdu_RecipeNER_Model.ipynb` file trains and tests the NER model on Urdu Recipes.
The `Combined.ipynb` runs the `Urdu_RecipeNER_Model` on the transcriptions saved in `Speech2Textpredictions.csv`.
