# fees_corpus
Text corpus annotated with Frame Evoking Elements.

Corpus data can be found here in the corresponding folder: https://disk.yandex.ru/d/VFlLy8FEKH8Dqg.

`validation` folder contains source code for automatic FEE annotation using RAG. The results of this automatic annotation can be accessed via the link above in the `GPT-4 Annotations` folder.

`validation_eval` folder contains source code for calculating metrics for automatic FEE annotation.

The texts annotated with Frames used data from the following resources:

- https://huggingface.co/datasets/HuggingFaceGECLM/REDDIT_threaded
- https://huggingface.co/datasets/fancyzhx/ag_news
- https://huggingface.co/datasets/MarcOrfilaCarreras/spanish-news
- https://huggingface.co/datasets/Kateryna/eva_ru_forum_headlines
- https://huggingface.co/datasets/IlyaGusev/gazeta
- https://www.kaggle.com/datasets/d0rj3228/russian-literature
- ```bibtex
  @article{baroni2009wacky,
  title={The WaCky wide web: a collection of very large linguistically processed web-crawled corpora},
  author={Baroni, Marco and Bernardini, Silvia and Ferraresi, Adriano and Zanchetta, Eros},
  journal={Language resources and evaluation},
  volume={43},
  number={3},
  pages={209--226},
  year={2009},
  publisher={Springer}
}```
- ```bibtex
  @article{pablo2019dataset,
  title={Dataset of discussion threads from Meneame},
  author={Pablo, Arag{\'o}n and Vicen{\c{c}}, G{\'o}mez and Andreas, Kaltenbrunner},
  journal={Dataset of discussion threads from Meneame},
  year={2019},
  publisher={Zenodo}
}```
- ```bibtex
  @InProceedings{espana-bonet-barron-cedeno-2024-elote-naacl,
    title = "Elote, Choclo and Mazorca: on the Varieties of {S}panish",
    author = "Espa{\~n}a-Bonet, Cristina  and
      Barr{\'o}n-Cede{\~n}o, Alberto",
    editor = "Duh, Kevin  and
      Gomez, Helena  and
      Bethard, Steven",
    booktitle = "Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.naacl-long.204",
    pages = "3689--3711"
}```
