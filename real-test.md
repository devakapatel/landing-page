# Real Test

## GitBook Markdown Showcase: All Features <a href="#gitbook-markdown-showcase-all-features" id="gitbook-markdown-showcase-all-features"></a>

This page demonstrates a comprehensive set of Markdown features supported by GitBook, including formulas, Mermaid diagrams, images, tables, code blocks, and more. Use this as a template or test page for your own GitBook projects.

### Table of Contents <a href="#table-of-contents" id="table-of-contents"></a>

* Headings & Text
* Lists
* Tables
* Code Blocks
* Formulas (LaTeX)
* Images
* Mermaid Diagrams
* Blockquotes
* Task Lists
* Footnotes

### Headings & Text <a href="#headings--text" id="headings--text"></a>

## H1 Heading <a href="#h1-heading" id="h1-heading"></a>

### H2 Heading <a href="#h2-heading" id="h2-heading"></a>

### H3 Heading

**Bold text**\
&#xNAN;_&#x49;talic text_\
~~Strikethrough~~\
\<sup>Superscript\</sup>\
\<sub>Subscript\</sub>

### Lists <a href="#lists" id="lists"></a>

* Unordered list item 1
* Unordered list item 2

1. Ordered list item 1
2. Ordered list item 2

### Tables <a href="#tables" id="tables"></a>

| Feature          | Supported | Example              |
| ---------------- | --------- | -------------------- |
| Tables           | Yes       | This table!          |
| Images           | Yes       | See below            |
| Mermaid Diagrams | Yes       | See diagrams section |
| LaTeX            | Yes       | See formulas section |

### Code Blocks <a href="#code-blocks" id="code-blocks"></a>

```
python# Python code example
def hello(name):
    print(f"Hello, {name}!")

hello("GitBook")
```

```
javascript// JavaScript code example
function greet(name) {
  console.log(`Hello, ${name}!`);
}
greet('GitBook');
```

### Formulas (LaTeX) <a href="#formulas-latex" id="formulas-latex"></a>

Inline formula: E=mc2E = mc^2E=mc2

Block formula:

∫−∞∞e−x2dx=π\int\_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}∫−∞∞e−x2dx=π

Quadratic formula:

x=−b±b2−4ac2ax = \frac{-b \pm \sqrt{b^2 - 4ac\}}{2a}x=2a−b±b2−4ac

### Images <a href="#images" id="images"></a>

!\[Sample Image]\([https://placekitten.comaid](https://placekitten.comaid) Diagrams

### Flowchart

```
textgraph TD
    A[Start] --> B{Is it working?}
    B -- Yes --> C[Great!]
    B -- No --> D[Fix it]
    D --> B
```

### Sequence Diagram

```
textsequenceDiagram
    participant User
    participant System
    User->>System: Sends request
    System-->>User: Returns response
```

### Gantt Chart

```
textgantt
    title Project Timeline
    dateFormat  YYYY-MM-DD
    section Development
    Design       :a1, 2025-05-01, 5d
    Coding       :after a1  , 10d
    Testing      : 3d
```

### Pie Chart

```mermaid
textpie
    title Project Distribution
    "Frontend" : 40
    "Backend" : 35
    "Security" : 25
```

### Entity Relationship Diagram

```mermaid
texterDiagram
    USER ||--o{ ORDER : places
    ORDER ||--|{ LINE_ITEM : contains
    PRODUCT ||--o{ LINE_ITEM : includes
```

### Blockquotes <a href="#blockquotes" id="blockquotes"></a>

> “The best way to predict the future is to invent it.”
>
> * Alan Kay

### Task Lists <a href="#task-lists" id="task-lists"></a>

* [x] Write Markdown content
* [x] Add Mermaid diagrams
* [x] Include code and formulas
* [ ] Test in GitBook

### Footnotes <a href="#footnotes" id="footnotes"></a>

Here is a statement with a footnote.[1](https://www.gitbook.com/integrations/mermaid)[1](https://www.gitbook.com/integrations/mermaid): This is the footnote text.

### Tips for Using Mermaid in GitBook <a href="#tips-for-using-mermaid-in-gitbook" id="tips-for-using-mermaid-in-gitbook"></a>

* Use triple backticks and the `mermaid` keyword to create diagrams.
* Ensure the Mermaid integration is enabled in your GitBook space for diagrams to render.[1](https://www.gitbook.com/integrations/mermaid)[5](https://sighingnow.github.io/jekyll-gitbook/jekyll/2023-08-31-mermaid.html)[8](https://docs.gitbook.com/help-center/integrations/existing-integrations/why-is-the-mermaid-block-not-loading)
* Explore more diagram types and syntax in the \[Mermaid documentation][2](https://mermaid.js.org/syntax/examples.html)[3](https://mermaid.js.org/intro/syntax-reference.html)[6](https://swimm.io/learn/mermaid-js/mermaid-js-a-complete-guide).

_Happy documenting with GitBook!_

#### Citations:

1. [https://www.gitbook.com/integrations/mermaid](https://www.gitbook.com/integrations/mermaid)
2. [https://mermaid.js.org/syntax/examples.html](https://mermaid.js.org/syntax/examples.html)
3. [https://mermaid.js.org/intro/syntax-reference.html](https://mermaid.js.org/intro/syntax-reference.html)
4. [https://github.com/mermaidjs/mermaid-gitbook/blob/master/content/flowchart.md?plain=1](https://github.com/mermaidjs/mermaid-gitbook/blob/master/content/flowchart.md?plain=1)
5. [https://sighingnow.github.io/jekyll-gitbook/jekyll/2023-08-31-mermaid.html](https://sighingnow.github.io/jekyll-gitbook/jekyll/2023-08-31-mermaid.html)
6. [https://swimm.io/learn/mermaid-js/mermaid-js-a-complete-guide](https://swimm.io/learn/mermaid-js/mermaid-js-a-complete-guide)
7. [https://github.com/TakuroFukamizu/gitbook-plugin-mermaid-newface](https://github.com/TakuroFukamizu/gitbook-plugin-mermaid-newface)
8. [https://docs.gitbook.com/help-center/integrations/existing-integrations/why-is-the-mermaid-block-not-loading](https://docs.gitbook.com/help-center/integrations/existing-integrations/why-is-the-mermaid-block-not-loading)
9. [https://xiaochen-su.gitbook.io/gitbook\_multilanguage\_template/node\_modules/gitbook-plugin-mermaid-compat](https://xiaochen-su.gitbook.io/gitbook_multilanguage_template/node_modules/gitbook-plugin-mermaid-compat)

***

Answer from Perplexity: pplx.ai/share
