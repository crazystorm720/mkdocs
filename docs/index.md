# Welcome to the Love Chronicles

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## The Mathematics of Love

Here's an example of an inline equation that describes the energy of love: \( L = hc^2 \).

And a display equation, because love deserves to be displayed prominently:

\[ L = hc^2 \]

## Love in Python Code

Here's a simple example of Python code that calculates the "love factor" of a person:

```python
def love_factor(heart):
    """Calculate the love factor of a person using recursion."""
    if heart == 0:
        return 1
    else:
        return heart * love_factor(heart-1)

# Example usage
heart_level = 5
print(f"The love factor of someone with a heart level of {heart_level} is {love_factor(heart_level)}")
```

The output of this code will be:

```
The love factor of someone with a heart level of 5 is 120
```

## Love, Inline and Sincere

You can also highlight your love messages like this: `print("I love you!")`.

## Annotated Love Letters

Here's an example of an annotated love letter:

```python
def love_letter(name):
    # This function sends a love letter to the person whose name is passed as a parameter
    return f"Dear {name},\nYou light up my life!\nLove, Your Secret Admirer"

# Example usage
print(love_letter("Alice"))  # Outputs: Dear Alice, You light up my life! Love, Your Secret Admirer
```

## Copy and Share the Love

You can easily copy the love letter code block above by clicking the copy button on the top right corner of the code block. Share the love!

## Snippets of Affection

You can include external snippets of affection with the `pymdownx.snippets` extension. Here's an example of including a snippet:

```
!!! include "path/to/love_snippet.py"
```

Ensure you have the file `love_snippet.py` in the specified path for this to work.

## Notes of Love

!!! note
    This is a note of love. You can use it to highlight important expressions of affection.

## Hidden Love Messages

You can hide love messages in expandable details sections:

<details>
<summary>Click to reveal a secret message</summary>

Here is some hidden love content that can be expanded and collapsed. You are loved!

</details>

## Footnotes of Love

Here's a statement with a footnote[^1].

[^1]: This is a loving footnote content.

## Highlighting Love

You can highlight your love notes using the `pymdownx.mark` extension. Here is some ==highlighted love==.
