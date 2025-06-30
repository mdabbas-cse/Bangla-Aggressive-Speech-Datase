# 🧠 Bangla Aggressive Speech Dataset (Targeting Religion)

This dataset contains Bangla-language comments labeled for **aggression** and **targeted religious hate speech**. It is designed to support research in Natural Language Processing (NLP), including aggression detection, hate speech moderation, and classification tasks focused on religious tolerance in online spaces.

---

## 📂 Dataset Overview

- **Language**: Bangla (বাংলা)
- **Domain**: Social Media, Online Comments
- **Total Samples**: *[add total rows, e.g. ~2,000]*  
- **Purpose**: Aggression classification and religious hate speech analysis

---

## 🧾 Data Format

Each row in the dataset includes:

| Column              | Description                                                |
|---------------------|------------------------------------------------------------|
| `Comments`          | The Bangla-language comment text                           |
| `Aggression Label`  | One of: `Aggressive`, `Non-Aggressive`                     |
| `Target Religion`   | The religion targeted in the comment (e.g., Hindu, Muslim) |

---

## 🔍 Sample Data

```csv
Comments,Aggression Label,Target Religion
তোরা কাফের, বাংলাদেশে থাকতে পারবি না।,Aggressive,Hindu
এটা সবার ধর্মের প্রতি সম্মান জানানোর দিন।,Non-Aggressive,
ধর্ম নিয়ে কথা বলবি তোকে কুত্তার মতো মারব।,Aggressive,Islam

```

## 🎯 Use Cases
This dataset is useful for:

- Hate speech and aggression detection in Bangla

- Religious bias classification

- Social media moderation tools

- Multilingual or cross-lingual NLP training

- Transfer learning for low-resource languages

languages

## 🧑‍💻 How to Use
You can load and analyze the dataset using pandas:
```python
import pandas as pd

df = pd.read_csv("bangla_aggression_dataset.csv")
print(df.head())
```

## 📚 Annotation Guidelines
[-] Aggressive: Includes threats, hate, or abuse.
- Non-Aggressive: Respectful, neutral, or irrelevant comments.
- Target Religion: Left blank if no religion is targeted.
Each comment was manually reviewed and annotated by native Bangla speakers.

## 📈 Statistics
(Fill these out based on your data)

- Aggressive: 1,245

- Non-Aggressive: 755

- Targeted Religions:

    - Hindu: 620
    
    - Islam: 420
    
    - Christian: 80
    
    - Buddhist: 45
    
    - None: 835

## 🪪 License
This dataset is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. You may use, distribute, and modify the dataset with attribution.

## 📣 Citation
If you use this dataset in your research, please cite it as:
```code
@dataset{abbas_2025_bangla_aggression,
  author       = {Abbas Uddin},
  title        = {Bangla Aggressive Speech Dataset with Religious Target Labels},
  year         = 2025,
  url          = {https://github.com/your-username/bangla-aggression-dataset},
  publisher    = {GitHub},
  license      = {CC-BY-4.0}
}
```

## 👥 Contributors

We gratefully acknowledge the contributions of the following individuals:

| Name                 | Role               | Affiliation           | GitHub Profile                          |
|----------------------|--------------------|------------------------|------------------------------------------|
| [Sharjina Afrin](https://github.com/SharjinaAfrin)       | Creator            | East Delta University | [@sharjina-afrin](https://github.com/SharjinaAfrin)      |
| [Kobra Elahi Fariya](https://github.com/kobra-fariya)     | Creator            | East Delta University | [@kobra-fariya](https://github.com/kobra-fariya)          |
| [Md. Abbas Uddin](https://github.com/mdabbas-cse)         | Annotator/Reviewer | East Delta University | [@mdabbas-cse](https://github.com/mdabbas-cse)            |



## 🤝 Contributions
Have additional labeled comments or want to help improve the dataset?
Feel free to fork this repo and submit a pull request or open an issue.

## ✅ How to use:
Add this under the ## Contributors section in your README.md.

Update GitHub links if necessary (for example: https://github.com/mdabbas-cse etc.).

If any of the contributors don’t have GitHub profiles yet, you can:

Leave the GitHub column blank for them.

Or just write their name as plain text without a link.

Let me know if you’d like to generate a CONTRIBUTORS.md file with short bios too!
