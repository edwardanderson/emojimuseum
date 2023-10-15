# Emoji Museum

Linked Art knowledge graph of emojis.

## Example

Describe an artwork with an arbitrary sequence of emojis: [🌃🥁💂🐕](https://edwardanderson.github.io/emojimuseum/text/🌃🥁💂🐕).

```json
{
    "@context": "https://linked.art/ns/v1/linked-art.json",
    "id": "http://www.wikidata.org/entity/Q219831",
    "type": "HumanMadeObject",
    "_label": "The Night Watch",
    "shows": [
        {
            "type": "VisualItem",
            "_label": "Visual work of The Night Watch",
            "subject_of": [
                {
                    "id": "https://edwardanderson.github.io/emojimuseum/text/🌃🥁💂🐕",
                    "type": "LinguisticObject",
                    "_label": "🌃🥁💂🐕"
                }
            ]
        }
    ]
}
```
