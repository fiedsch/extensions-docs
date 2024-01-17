---
title: "Insert tags"
weight: 6
---


Several insert tags are provided to ease handling of multilingual websites
with *ChangeLanguage*. Basically, [the Contao core link insert tags][1] are
supported with a `changelanguage_` prefix and language suffix.

The page reference can either be the database ID or the page alias.

### Examples

1. `{{changelanguage_link::15::fr}}`

    Generates a link to the french version of page ID 15.

2. `{{changelanguage_link_open::15::de}}`

    Generates the opening anchor for linking to the German version of page ID 15.

3. `{{changelanguage_link_url::15::en}}`

    Returns the URL to the English version of page ID 15.

4. `{{changelanguage_link_title::15::it}}`

    Returns the title of the Italian version for page ID 15.

5. `{{changelanguage_link_name::15::es}}`

    Returns the name of the Spanish version of page ID 15.


[1]: https://docs.contao.org/books/manual/3.5/en/04-managing-content/insert-tags.html#link-elements
