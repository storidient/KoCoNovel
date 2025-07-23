# KoCoNovel
KoCoNovel is a character coreference dataset based on 50 modern and contemporary Korean novels. For more details, refer to our paper, "[KoCoNovel: Annotated Dataset of Character Coreference in Korean Novels](https://arxiv.org/abs/2404.01140)".

## Updates
- [2025-02] We now provide the dataset in both CoNLL and JSONL formats for easier processing and integration.
- [2025-02] Added speaker assignment annotations for all direct quotations in the dataset.
---

## Corpus
The corpus is drawn from the public domain texts on [Wikisource](https://ko.wikisource.org/wiki/). The preprocessing involved correcting typos and incorrect line breaks within the text, and adjusting the spelling to match modern Korean grammar. The list of novels can be found in the file `list_of_novels.csv`.

## Data and Annotation
KoCoNovel contains grammatically corrected versions of novels and annotations for character coreference in four types of options, along with speaker annotations for all direct quotations. The types of options are as follows:

- **[Reader/Omniscient]** From the perspective of the omniscient author or the readers
- **[Separate/Overlapped]** How multiple entities are treated either as separate entities (e.g., [‘We’], [‘I’], [‘You’]) or as overlapped entities (e.g., [‘We’, ‘I’], [‘We’, ‘You’]) 

## License

This dataset is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

Please cite the following work if you use this dataset:
```
@misc{kim2024koconovel,
      title={KoCoNovel: Annotated Dataset of Character Coreference in Korean Novels}, 
      author={Kyuhee Kim and Surin Lee and Sangah Lee},
      year={2024},
      eprint={2404.01140},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```


