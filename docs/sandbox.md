---
comments: true
---

# Welcome to MkDocs

::cards:: cols=2

- title: Zeus
  content: Lorem ipsum dolor sit amet.
  url: https://en.wikipedia.org/wiki/Zeus

- title: Athena
  content: Lorem ipsum dolor sit amet.

::/cards::

  [Language]: changing-the-language.md
  [Navigation]: setting-up-navigation.md
  [Header]: setting-up-the-header.md
  [Footer]: setting-up-the-footer.md
  [Search]: setting-up-site-search.md
  [Tags]: setting-up-tags.md

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

==This was marked==
^^This was inserted^^
~~This was deleted~~

$$
A = B ^ {100}
$$

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```

```cpp linenums="1" hl_lines="2 3"
int main() {
  
  return 0;
}

```

<!---
  コメント
-->
