---
{"dg-publish":true,"permalink":"/015-code-blocks/"}
---

These codeblocks should not be modified upon publish.

Sample 1
```jinja2
{{ highlight_text }}{% if highlight_location and highlight_location_url %} ([via]({{highlight_location_url}})){% elif highlight_location %} ({{highlight_location}}){% endif %}
{ #rwhi}
{{highlight_id}}
{% if highlight_note %}
{{ highlight_note }}
{ #rwhi}
{{highlight_id}}_note
{% endif %}
```

Sample 2
```md
In medieval Latin a florilegium (plural florilegia) was a compilation of excerpts from other writings.
 The word is from the Latin flos (flower) and legere (to gather): literally a gathering of flowers, or collection of fine extracts from the body of a larger work. ([via](https://en.wikipedia.org/wiki/Florilegium))
{ #rwhi724352030}

```