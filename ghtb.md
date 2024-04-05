```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```


Markdown Preview Mermaid Support


Adds Mermaid diagram and flowchart support to VS Code's builtin Markdown preview and to Markdown cells in notebooks.

A mermaid diagram in VS Code's built-in markdown preview

Currently supports Mermaid version 10.8.0.

Usage
Create diagrams in markdown using mermaid fenced code blocks:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
You can also use ::: blocks:

::: mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
:::

Markdown Preview Mermaid Support


Adds Mermaid diagram and flowchart support to VS Code's builtin Markdown preview and to Markdown cells in notebooks.

A mermaid diagram in VS Code's built-in markdown preview

Currently supports Mermaid version 10.8.0.

Usage
Create diagrams in markdown using mermaid fenced code blocks:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
You can also use ::: blocks:

::: mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
:::
Configuration
markdown-mermaid.lightModeTheme — Configures the Mermaid theme used when VS Code is using a light color theme. Supported values are: "base", "forest", "dark", "default", "neutral". Currently not supported in notebooks.

markdown-mermaid.darkModeTheme — Configures the Mermaid theme used when VS Code is using a dark color theme. Supported values are: "base", "forest", "dark", "default", "neutral". Currently not supported in notebooks.

markdown-mermaid.languages — Configures language ids for Mermaid code blocks. The default is ["mermaid"].

Using custom CSS in the Markdown Preview
You can use the built-in functionality to add custom CSS. More info can be found in the markdown.styles documentation

For example, add Font Awesome like this:

"markdown.styles": [
    "https://use.fontawesome.com/releases/v5.7.1/css/all.css"
]
Use it like this:

```mermaid
graph LR
    fa:fa-check-->fa:fa-coffee
```
# List:Dançarinos.
```mermaid
graph TD;

    A-->1;
    A-->2;
    A-->3;
    A-->4;

```

# Preparação com Dançarinos:
```mermaid
graph TD
Abizael-->2024
Alan-->2024
Gabriella-->2024
Ricardo-Bastos-->Abizael
B-->Abizael
1C-->Alan
1C-->Gabriella
```

#  Uma Nova Lista:

```mermaid
graph TD
A-->q
B-->w
C-->L
GH-->we
qwe-->qw
whatt-->23
2BA--->12d
2id--->12
23-->wer
12-->we
gh-->q
AA-->21-->43::--->43
BB-->23::232[12]
i1-->2122{
TD--->78
TD-->23 
DT-->100%
78-->po
A-->-0 
}
BG-->87
TG-->12
C--->we
K--->12
kl-->12
87-->BC
```
