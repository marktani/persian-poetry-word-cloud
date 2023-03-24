# persian-poetry-word-cloud

Generating word clouds for Persian poetry.

## Installation

```sh
pip3 install python-bidi arabic_reshape
```

## Running

```sh
jupyter notebook
# open `persian-word-cloud.ipynb`
```

## References

- Corpus: We are using the poetry of Hafez, Rudaki, Saadi, Molana, and Khayyam kindly provided in this [Persian poems corpus](https://github.com/amnghd/Persian_poems_corpus), considering the variant with all stepwords removed.
- Libraries: Python 3, [word_cloud](https://github.com/amueller/word_cloud), [arabic_reshaper](https://pypi.org/project/arabic-reshaper/), [python-bidi](https://pypi.org/project/python-bidi/).
- Code: The code was adapted based on [this example](http://amueller.github.io/word_cloud/auto_examples/arabic.html#sphx-glr-auto-examples-arabic-py) from the `word_cloud` documentation.
- Font: we are using the `Noto Naksh Arabic` font in the regular variant, obtained from [Google Fonts](https://fonts.google.com/noto/specimen/Noto+Naskh+Arabic?query=noto&subset=arabic&noto.script=Arab).
