# Algerian (darija dziria) Dialect Comments Dataset

## Overview

A dataset of approximately **10,850 Algerian Arabic comments** collected from YouTube videos covering different topics: **music, cooking, traditions, cars, gaming, and comedy/TV shows News**.

The dataset is designed to support **NLP research on the Algerian dialect**, which has limited available resources.

## Statistics

* **Comments:** ~10850 
* **Videos:** 50+
* **Categories:** 19
* **Average comment length:** >3 

## Data Collection

Comments were collected from Algerian YouTube channels using `youtube-comment-downloader`.

The data was cleaned by:

* Removing very short/long comments
* Removing spam, links, and empty comments
* Removing duplicates
* Filtering obvious non-Algerian dialect comments
* Removing mention-only comments

## Data Structure

| Column      | Description                              |
| ----------- | ---------------------------------------- |
| `text`      | Original comment                         |
| `video_url` | Source YouTube video                     |
| `category`  | Video category                           |
| `sentiment` | Positive (1), Neutral (0), Negative (-1) |
| `likes`     | Number of likes, if available            |

## Sentiment

Sentiment labels were generated using Algerian Arabic positive and negative keywords:

* **1** = Positive
* **0** = Neutral
* **-1** = Negative

## Limitations

* The dataset does not represent all Algerian regional dialects.
* YouTube comments may reflect mostly online and younger users.
* Dialect filtering is keyword-based and may contain some errors.
* Sentiment labels are automatically generated and may not be 100% accurate.
* Natural spelling variations and Arabic/French/English code-switching are preserved.

## Possible Uses

* Algerian Arabic sentiment analysis
* Dialect identification
* NLP model fine-tuning
* Linguistic and code-switching research

## License

**CC BY 4.0** — The dataset can be used, modified, and shared with proper attribution.

## Citation

> [khadidja-Mha]. (2026). *Algerian (darija dziria) Dialect Comments Dataset*. GitHub.

## Contact
if you need 
For questions or suggestions: **www.linkedin.com/in/khadidja-m-88909b3a4**
"# darija_dz_-213" 
