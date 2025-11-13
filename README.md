# espanso-lipsum
A simple package to generate random lorem ipsum sentences or paragraphs based on free macOS app [LoremBuilder](https://lorembuilder.com/).

Forked to add double spacing between paragraphs, so I don't have to keep adding spaces in WordPress.

All credit to Dominique Da Silva for [the original](https://github.com/atika/espanso-lorem).

For more information, read the [documentation](https://espanso.org/docs/)

### Installation

```
espanso install lipsum --git https://github.com/Alexx916/espanso-lipsum --external
espanso restart
```

### Usage

|  Trigger  | Replace |
|-----------|---------|
| `>lipsum`  | 1 sentence. |
| `>2lipsum` | 2 sentences. |
| `>3lipsum` | 3 sentences. |
| `>4lipsum` | 4 sentences. |

|  Trigger  | Replace |
|-----------|---------|
| `#lipsum`  | 1 paragraph. |
| `#2lipsum`  | 2 paragraphs. |
| `#3lipsum`  | 3 paragraphs. |
| `#4lipsum`  | 4 paragraphs. |
