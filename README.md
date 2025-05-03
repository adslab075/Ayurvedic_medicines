Ayurvedic Medicines Dataset
This repository contains a dataset of Ayurvedic medicines used in traditional Indian healthcare systems. The data is structured in a CSV file and includes details such as:

Medicine Name

Formulation Type

Key Ingredients

Dosha Balancing Properties (Vata, Pitta, Kapha)

Common Uses / Indications

📂 File Included
Ayurvedic_medicines.csv — Main dataset with detailed information about various Ayurvedic medicinal formulations.

🔍 Purpose
This dataset can be used for:

Research and analysis of Ayurvedic formulations

Integrating into health recommendation systems

Educational purposes for students and practitioners of Ayurveda

Building ML/NLP models for health prediction or formulation recommendation

📊 Sample Columns
Medicine Name	Type	Ingredients	Targets Dosha	Common Uses
Triphala	Powder	Amalaki, Haritaki, Bibhitaki	Vata, Pitta, Kapha	Digestion, Detox
Ashwagandha	Tablet	Withania somnifera	Vata	Stress, Fatigue

💡 Usage
You can load and use the dataset in Python using:

python

import pandas as pd

df = pd.read_csv('Ayurvedic_medicines.csv')
print(df.head())


📜 License
This dataset is provided for educational and research purposes only. Please consult an Ayurvedic practitioner for medical advice.
