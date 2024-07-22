# ExaAUAC
ExaAUAC is presented to detect the age of Arabic Twitter users. It is a large-scale corpus including 181k user profiles with diverse age groups consisting of −18, 18–24, 25–34, 35–49, 50–64, +65.
The key advantage of presented corpus is the large size of data with balance in different classes.

## Data
All IDs, names and usernames are fake to protect users' privacy.


## Results
Our results show that the accuracy of the user age detection model based on ExaAUAC corpus, can be increased by using the BERT language model in combination with chunking text of tweets and user information.
The model achieved macro-averaged F1-score of 44 on six age groups, and F1-score of 58 on three age groups of −25, 25–34, +35. 

## Future Releases
In the future, ExaAUAC will expand the data in class of +65 and also will cause increase in accuracy of age detection model by using better language model.

## Citation
Please cite the following <a href="https://link.springer.com/article/10.1007/s44163-024-00145-0">paper</a> in your publication if you are using ExaAUAC in your research:

```
@article{ExaAUAC ,
    title={ExaAUAC: Arabic Twitter User Age prediction Corpus based on language and metadata features},
    author={Sadeghi, Reyhaneh, Ahmad Akbari, and Mohammad Mehdi Jaziriyan},
    journal={ Discover Artificial Intelligence},
    year={2024},
    volume={Volume 4,Issue 1}
}
```

