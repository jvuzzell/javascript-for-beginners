# Document Object Model (DOM) Representation

The Document Object Model (DOM) represents the structure of an HTML or XML document as a tree-like structure. Below is an ASCII representation to help visualize how different elements are connected.

```
                    [Document]
                        |
                        |
                    [html]
                    /     \
                   /       \
               [head]     [body]
                /            |
               /             |
           [title]       [div]
              |             / | \
              |            /  |  \
           "My Page"   [h1] [p] [ul]
                            |    |   |
                            |    |   [li]
                          "Hello" |   |
                                "Intro" [li]
                                          |
                                        "Item 1"
```

### Explanation:

- **[Document]**: Represents the entire HTML or XML document.
- **[html]**: The root element, containing both the `<head>` and `<body>` elements.
- **[head]**: Contains metadata for the document, such as the `<title>`.
- **[title]**: The title of the page, represented here as "My Page".
- **[body]**: Contains the content of the document.
- **[div]**: A generic container element that can group different sections.
- **[h1]**: Represents a level-1 heading, here containing the text "Hello".
- **[p]**: Represents a paragraph, containing the text "Intro".
- **[ul]**: An unordered list containing list items (`<li>`).
- **[li]**: Each list item, in this case, represents "Item 1".

### Notes:
- The DOM is represented as a tree structure, where each node corresponds to an HTML element.
- The indentation and branches illustrate the parent-child relationships.
- Text nodes (e.g., "My Page", "Hello") are children of their respective HTML tags.
