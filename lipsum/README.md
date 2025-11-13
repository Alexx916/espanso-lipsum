---
package_name: "lipsum"
package_title: "Lorem Ipsum"
package_desc: "Lorem ipsum sentences and paragraphs generator."
package_version: "0.1.0"
package_author: "Alex Hopkin"
package_repo: "https://github.com/alexx916/espanso-lipsum"
---
A simple package to generate random lorem ipsum sentences or paragraphs based on free macOS app [LoremBuilder](https://lorembuilder.com/).

Forked to add double spacing between paragraphs, for use with WordPress and the like.

### Installation

```
espanso install lipsum --git https://github.com/Alexx916/epsanso-lipsum --external
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
