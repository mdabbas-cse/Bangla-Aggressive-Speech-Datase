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
