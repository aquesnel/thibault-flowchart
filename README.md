# thibault-flowchart

This project is a flowchart of all the fencing plays in the book "Academie de l'espee" by Girard Thibault from 1628.

# Goal

The goal of this project is to have a flowchart that:
* shows the sequence of circles for each play in the book. 
* highlights the decisions points and choices that Thibault makes for in each play in the book.

# Plan

The plan for this project is: 
1. create 1 flowchart for each chapter exactly following the circles in the book and just create the graph of nodes with just the circle number in the node. Do this for all chapters, and one file per chapter. 
2. For each chapter add nodes for the decision points and options that Thibault calls out in the text. Fill in those questions and the options so the graph is a self sufficient flowchart.
3. Combine the chapters into one flowchart and merge overlapping parts of plays across chapters that are repeated moves.
4. add the ability to focus any play and related decisions.

# Contributing

## Guidelines

When contributing to this project please follow these guidelines: 
* Content/code:
  * commit messages use the [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/) format.
  * the naming convention used for chapters in the book is: `Book # Tabula #` to match the the naming used by Thibault.
  * the naming convention used for node ids in the flowchart that represent a circle in the book is: `B#_T#_C#` This naming convention allows circles to reference any other circle in the book. 
* Fact checking: 
  * provide a reference to the flowchart and nodes with an error, as well as a reference to the relevant sections of the book. Book references should be in the form: book#-tabula# or chapter#; section name such as - introduction, circle#, figure#, or conclusion; and paragraph#.
 
## How to Edit a flowchart

### GUI editing and live text preview

* open a browser to one of the GUI editors (eg. https://www.mermaidflow.app/editor )
* Copy/paste the text of an `.mmd` mermaid file into the text area
* Edit the flowchart
* Copy/paste the text from the text area into an `.mmd` mermaid file

### Quick edit links

These are quick links to the https://mermaid.live/ site with the given chapter flowchart loaded. For GUI editing click the "Playground" toggle. Once you are done editing, you'll need to copy the mermaid text from the editor and paste it into the `flowchart-per-chapter/chapter-??.mmd` file in github and commit it.

| Tablua / Chapter | Edit in Mermaid.live                                                                                                                                      | Save in Github                                                                                        |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| 5                | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-05.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-05.mmd) |
| 6                | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-06.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-06.mmd) |
| 7                | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-07.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-07.mmd) |
| 8                | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-08.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-08.mmd) |
| 9                | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-09.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-09.mmd) |
| 10               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-10.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-10.mmd) |
| 11               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-11.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-11.mmd) |
| 12               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-12.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-12.mmd) |
| 13               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-13.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-13.mmd) |
| 14               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-14.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-14.mmd) |
| 15               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-15.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-15.mmd) |
| 16               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-16.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-16.mmd) |
| 17               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-17.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-17.mmd) |
| 18               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-18.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-18.mmd) |
| 19               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-19.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-19.mmd) |
| 20               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-20.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-20.mmd) |
| 21               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-21.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-21.mmd) |
| 22               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-22.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-22.mmd) |
| 23               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-23.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-23.mmd) |
| 24               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-24.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-24.mmd) |
| 25               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-25.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-25.mmd) |
| 26               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-26.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-26.mmd) |
| 27               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-27.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-27.mmd) |
| 28               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-28.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-28.mmd) |
| 29               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-29.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-29.mmd) |
| 30               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-30.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-30.mmd) |
| 31               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-31.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-31.mmd) |
| 32               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-32.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-32.mmd) |
| 33               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-33.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-33.mmd) |
| 34               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-34.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-34.mmd) |
| 35               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-35.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-35.mmd) |
| 36               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-36.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-36.mmd) |
| 37               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-37.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-37.mmd) |
| 38               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-38.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-38.mmd) |
| 39               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-39.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-39.mmd) |
| 40               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-40.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-40.mmd) |
| 41               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-41.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-41.mmd) |
| 42               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-42.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-42.mmd) |
| 43               | [Edit](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-43.mmd) | [Save](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-43.mmd) |


# Resources

## Tools

Mermaid GUI Editor
* https://www.mermaidflow.app/editor
  * Pro:
	* GUI editing makes minimal changes to the TEXT version
	* Easy to use and edit the flowchart
  * Cons:
    * The default edge type does not have an arrow in the text but is rendered with an arrow. 
* https://www.mermaidchart.com/play
  * Pro:
    * Easy to use
  * Cons:
    * GUI editing re-writes the text
* https://mermaidviewer.com/editor
  * Pro:
  * Cons:

## References

Interactive diagrams:

* Marmaid JS events:
  * https://mermaid.js.org/syntax/flowchart.html#interaction
  * https://mermaid.js.org/config/usage.html#binding-events
* Marmaid Chart docs: https://docs.mermaidchart.com/mermaid-oss/syntax/flowchart.html#interaction
* making SVG images clickable: https://www.freecodecamp.org/news/how-to-make-clickable-svg-map-html-css/ 

Mermaid.live URL embeded graph using base64 or "pako" encoding:

* https://github.com/mermaid-js/mermaid-live-editor/discussions/1291#discussioncomment-6837936
* Note: base64 encoding is also supported, as long as the graph is wrapped in the following json: `{"code": "<MERMAID_GRAPH_TEXT>" }`
  * ex: https://mermaid.live/view#base64:eyJjb2RlIjoiZmxvd2NoYXJ0IExSXG5FTkRfRVhFQ1VURUQoKGVuZCkpXG5QUk9DRVNTX1NUQVJUKChzdGFydCkpXG5QUk9DRVNTX1NUQVJUIC0tPiBFTkRfRVhFQ1VURUQifQ
