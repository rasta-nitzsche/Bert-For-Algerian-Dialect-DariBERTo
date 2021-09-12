# Bert-For-Algerian-Dialect-DariBERTo

## About
We developped 2 BERT models that can understand Algerian dialect (Darija).
One model is from scratch (You should execute the code on a server for many hours to train the model as we could not do this), we called it DariBERTo.
One pretrained model for the Arabic language from moha. Link: https://huggingface.co/moha/arabert_c19.

## Data Collection
We got the needed data by web scrapping via APIs three social networks: Facebook, Twitter, YouTube. We got over 500 000  raw data but will shorten due to the preprocessing.

## Preprocessing
Delete URL's, ponctuation, repeated caracters, additionnal blanks, numbers and emojis.
Normalize arabic numbers that means letters by subbing them with their correct value (.kh=5, h=7,q=9, ou=2, t=6).
Some manual cleaning with excel to avoid some sentences with no sense.

## Credits
CodeEmporium playlist for Transformers: https://www.youtube.com/watch?v=TQQlZhbC5ps&list=PLTl9hO2Oobd_bzXUpzKMKA3liq2kj6LfE&ab_channel=CodeEmporium.

Transformers from scratch: https://towardsdatascience.com/transformers-from-scratch-creating-a-tokenizer-7d7418adb403.

Krish Naik Deep playlist for BERT implementation: https://www.youtube.com/watch?v=DkzbCJtFvqM&list=PLZoTAELRMXVOTsz2jZl2Oq3ntWPoKRKwv&ab_channel=KrishNaik.

Search paper for BERT: https://arxiv.org/pdf/1810.04805.pdf.
