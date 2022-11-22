# Deck Name

## Flashcard A

Front of card A, will demo how to define the back of a card using the `md2apkg split` label

<!-- md2apkg split -->

(Instead of the `md2apkg split` syntax, you can also flip a card using the percent sign `%`)

This is the back of flashcard A.

Using Markdown, you can emphasize text with *italics*, or **bold** depending on the number of asterisks. _underscores_ __also work__.

You can make `inline code` using backticks

```
You can also
define code blocks
using triple backticks like so
```

Be careful with triangle brackets `<` and `>`, they're interpreted as HTML tags, meaning they won't be rendered, unless you're very careful with using escape characters first.  Better just to avoid them where possible.

This isn't required, but three hyphens to separate flashcards will render very nicely in Markdown, and keep flashcards in thie same Markdown file cleanly separated visually.

---

## Flashcard B

<!-- md2apkg type multiple-choice -->

The `md2apkg type multiple-choice` label lets you create a multiple-choice flashcard: (select Option A and Option C before checking your answer (in Anki))

- [X] Option A
- [ ] Option B
- [x] Option C
