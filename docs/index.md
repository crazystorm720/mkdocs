# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Math Example

Here's an example of an inline equation: \( E = mc^2 \).

And a display equation:

\[ E = mc^2 \]

## Python Code Example

Here's a simple example of Python code that calculates the factorial of a number:

```python
def factorial(n):
    """Calculate the factorial of a number using recursion."""
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)

# Example usage
number = 5
print(f"The factorial of {number} is {factorial(number)}")
```

The output of this code will be:

```
The factorial of 5 is 120
```

## Inline Code Example

You can also highlight inline code like this: `print("Hello, World!")`.

## Code Annotation Example

Here's an example with code annotation:

```python
def greet(name):
    # This function greets the person whose name is passed as a parameter
    return f"Hello, {name}!"

# Example usage
print(greet("Alice"))  # Outputs: Hello, Alice!
```

## Code Copy Button Example

You can easily copy the code block above by clicking the copy button on the top right corner of the code block.

## Snippet Example

You can include external code snippets with the `pymdownx.snippets` extension. Here's an example of including a snippet:

```
!!! include "path/to/snippet.py"
```

Ensure you have the file `snippet.py` in the specified path for this to work.

## Admonition Example

!!! note
    This is an admonition note example. You can use it to highlight important information.

## Details Example

You can hide content in expandable details sections:

<details>
<summary>Click to expand</summary>

Here is some hidden content that can be expanded and collapsed.

</details>

## Footnotes Example

Here's a statement with a footnote[^1].

[^1]: This is the footnote content.

## Highlighted Text Example

You can highlight text using the `pymdownx.mark` extension. Here is some ==highlighted text==.

