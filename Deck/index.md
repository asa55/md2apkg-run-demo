# Deck Name

## Flashcard A

Front of card A, will demo how to define the back of a card using the `md2apkg split` label

<!-- md2apkg split -->

This is the back of card A.

Using Markdown, you can emphasize text with *italics*, or **bold** depending on the number of asterisks. _underscores_ __also work__.

You can make `inline code` using backticks

```
You can also
define code blocks
using triple backticks like so
```

Be careful with triangle brackets `<` and `>`, they're interpreted as HTML tags, meaning they won't be rendered, unless you're very careful with using escape characters first.  Better just to avoid them where possible.

#### Another flashcard

Notice the extra hash.  You can use between 1 and 6 hashes in a row.  This means something special in HTML, but for building your flashcard deck, it basically means the header text on a flashcard with more hashes in the header will render as smaller, less bold text.  That is to say, if you are reading this in Anki, you'll notice the header text is smaller when compared to Flashcard A.

(Instead of the `md2apkg split` syntax, you can also flip a card using the percent sign, as shown below)

%

Note that the single hash defining Deck Name isn't special, if you want you can use more hashes before defining the Deck Name and it won't break anything.  Similarly, you can use single-hashes to define flashcard headers.  For convenience, I follow a convention that makes sense to me by putting a single hash in front of the Deck Name, and the same number of hashes in the headers of my flashcards.  But the point I'm noting here is that this convention is not strictly required. Feel free to deviate from my conventions if you feel so inclined. It won't break anything.

##### A multiple choice flashcard

<!-- md2apkg type multiple-choice -->

The `md2apkg type multiple-choice` label lets you create a multiple-choice flashcard: (select Option A and Option C before checking your answer (in Anki))

- [X] Option A
- [ ] Option B
- [x] Option C
