# lingua podre

dead simple word list based pure python language detector


## Install

```bash
pip install lingua_podre
```

## Usage

```python
from lingua_podre import predict_lang, get_lang_scores

utterance = "hello my name is Bob"
utterance_pt = "olá o meu nome é João"

print(predict_lang(utterance))
# ['en']
print(get_lang_scores(utterance))
# {'en': 0.2727272727272727, 'pl': 0.09090909090909091, 'cs': 0.09090909090909091, 'sk': 0.09090909090909091, 'hu': 0.09090909090909091, 'sv': 0.09090909090909091, 'nb': 0.09090909090909091, 'da': 0.09090909090909091, 'nl': 0.09090909090909091}

print(predict_lang(utterance_pt))
# ['pt']
print(get_lang_scores(utterance_pt))
# {'pt': 0.2857142857142857, 'ca': 0.07142857142857142, 'pl': 0.07142857142857142, 'cs': 0.07142857142857142, 'ro': 0.14285714285714285, 'it': 0.14285714285714285, 'tr': 0.07142857142857142, 'sk': 0.07142857142857142, 'es': 0.07142857142857142}
```

## Available languages

* Arabic
* Bulgarian
* Catalan
* Czech
* Danish
* Dutch
* English
* Finnish
* French
* German
* Gujarati
* Hindi
* Hebrew
* Hungarian
* Indonesian
* Malaysian
* Italian
* Norwegian
* Polish
* Portuguese
* Romanian
* Russian
* Slovak
* Spanish
* Swedish
* Turkish
* Ukrainian
* Vietnamese