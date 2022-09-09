# INDspeech06: INDspeech_NEWS_EthnicSR

This is a collection of Indonesian ethnic speech corpora for Javanese and Sundanese for Indonesian ethnic speech recognition. It was developed in 2012 by the Nara Institute of Science and Technology (NAIST, Japan) in collaboration with the Bandung Institute of Technology (ITB, Indonesia) [[Sani et al., 2012](https://ieeexplore.ieee.org/document/6422469)].

## Text and Speech Resources

The raw text source is based on Javanese and Sundanese newspapers/magazines. We then selected phonetically-balanced sentences from the raw text data. A minimum set with a total of 230 sentences is produced using [the greedy search algorithm](https://www.internationalphoneticassociation.org/icphs-proceedings/ICPhS2003/papers/p15_3145.pdf). 

|       Attributes     | Javanese | Sundanese | 
| --------------- | ------- |------------ |
| Number of Sentences     |      230 |           230 | 
| Number of Words   |     2999 |         4262 | 
| Vocabulary Size  |     1529 |         1728 | 

After that, 20 native speakers were selected, 10 native speakers (5 males and 5 females) from Java ethnicity and the other 10 native speakers (5 males and 5 females) from Sunda ethnicity. Then, each speaker was asked to read the prepared text of the 230 sentences. Each audio file is a single-channel 16-bit PCM WAV with a sample rate of 16 kHz.

## File Format

```
"Jaw001_F_B_C_news_0065.wav" 
```

- Speaker ID: JawXXX for Javanese speakers and SndXXX for Sundanese speakers
- Gender ID: F or M
- Accent sentence ID: J (Javanese) for Javanese sentences and S (Sundanese) for Sundanese sentences
- Type ID: C (Clean) 
- Content ID: news
- Utterance ID: XXXX 

## Pronunciation Dictionary

Here we also provide the pronunciation lexicon of Javanese and Sundanese (see Jawa/text/pronunciation.lex and Sunda/text/pronunciation.lex).

The format of the pronunciation dictionary is:
```
WORD PHN_1 PHN_2 ... PHN_N
```
Example:
```
elek	E L E K 
gaweyan	G A W E Y A N 
```

## License

This data is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) International License (see LICENSE_CC-BY-NC-4.0.txt). You can use the data free for non-commercial purposes, but you have to cite our paper if your work uses our data in your publication. If you remix, transform or build upon the material, you must distribute your contributions under the same license as the original. Furthermore, you are not allowed to create a copy of this dataset and share it publicly in your own repository without our permission.

## Citation

Please cite the following papers:

[[Sani et al., 2012](doc/2012_ssakti_OCOCOSDA.pdf)]:

```
@inproceedings{sani-cocosda-2012,
    title = "Towards Language Preservation: Preliminary Collection and Vowel Analysis of {I}ndonesian Ethnic Speech Data",
    author = "Sani, Auliya and Sakti, Sakriani and Neubig, Graham and Toda, Tomoki and Mulyanto, Adi and Nakamura, Satoshi",
    booktitle = "Proc. Oriental COCOSDA",
    year = "2012",
    pages = "118--122"
    address = "Macau, China"
}
```
