# KoCoNovel
KoCoNovel is a character coreference dataset based on 50 modern and contemporary Korean novels. For more details, refer to our paper, "[KoCoNovel: Annotated Dataset of Character Coreference in Korean Novels](https://arxiv.org/abs/2404.01140)".

## Corpus
The corpus is drawn from the public domain texts on [Wikisource](https://ko.wikisource.org/wiki/). The preprocessing involved correcting typos and incorrect line breaks within the text, and adjusting the spelling to match modern Korean grammar. The list of novels can be found in the file `list_of_novels.csv`.

## Data and Annotation
KoCoNovel contains grammatically corrected versions of novels and annotations for character coreference in four types of options, along with speaker annotations for all direct quotations. The types of options are as follows:

* **[Reader/Omniscient]** From the perspective of the omniscient author or the readers
  
|Phenomenon|Reader|Omniscient|
|---|---|---|
|"Oh, {Taehoon}! Would that really be okay?"
It was the melodious voice of a woman.
"If {Kyungsuk} likes it, how happy {I} would be."
{The man}’s voice was clear, filled with passion. ... 
What a weird scene! The lights were still on,
but the bed was covered with what looked like
love letters sent to students, all scattered around.
In the middle of this mess, {Ms. B} sat up alone. ...
With a face that looked kind of funny and
desperate, {she} seemed to be waiting for a kiss.
At the same time, {she} tried to sound like a man.]|[Taehoon, I, The man], [Kyungsuk], [Ms. B,
she, she]|[Taehoon, I, The man, Kyungsuk, Ms. B,
she, she]|

* **[Separate/Overlapped]** How multiple entities are treated either as separate entities

In the data folder, there are three folders:





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


