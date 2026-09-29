# 🇩🇿 Algerian Darija Comments Dataset

![License](https://img.shields.io/badge/license-CC%20BY%204.0-blue)
![Comments](https://img.shields.io/badge/comments-~10k-green)
![Language](https://img.shields.io/badge/language-Algerian-orange)
![Source](https://img.shields.io/badge/source-YouTube-red)

A dataset of **~10,000 Algerian  (Darija) comments** from YouTube, covering music, cooking, traditions, cars, gaming, and comedy/TV... Built to support **NLP research on the Algerian dialect**, which has few available resources.

[Stats](#-stats) • [Files](#-files) • [Data Structure](#️-data-structure) • [Limitations](#️-limitations) • [License](#-license)

## 📊 Stats

| Comments | Videos | Categories |
| :------: | :----: | :--------: |
| ~10,000  |  20+   |     19     |

## 📁 Files

| File | Description |
| ---- | ----------- |
| [darijaALGdz213.xlsx](darijaALGdz213.xlsx) | YouTube comments dataset |
| [dz darija.xlsx](dz%20darija.xlsx) | Darija–MSA–English-Arabic dictionary |

## 🗂️ Data Structure

| Column      | Description                              |
| ----------- | ---------------------------------------- |
| `text`      | Original comment                         |
| `video_url` | Source YouTube video                     |
| `category`  | Video category                           |
| `sentiment` | `1` Positive, `0` Neutral, `-1` Negative |
| `likes`     | Number of likes (if available)           |

## ⚙️ Collection & Cleaning

Collected with `youtube-comment-downloader`, then cleaned by removing spam and links, empty, very short or very long comments, duplicates, mention-only comments, and obvious non-Algerian dialect.

Sentiment labels were generated automatically from Algerian positive/negative keywords.

## ⚠️ Limitations

- Does not cover all Algerian regional dialects
- Mostly reflects online and younger users
- Dialect filtering and sentiment labels are automatic and may contain errors
- Spelling variations and Arabic/French/English code-switching are kept

## 💡 Use Cases

Sentiment analysis • Dialect identification • Model fine-tuning • Code-switching research

## 📄 License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): free to use, modify, and share with attribution.

## 📚 Citation

```
Khadidja-Mha. (2026). Algerian (Darija Dziria) Dialect Comments Dataset. GitHub.
```

## 📬 Contact

Questions or suggestions: [LinkedIn](https://www.linkedin.com/in/khadidja-m-88909b3a4)