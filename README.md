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

* chapter-05.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-05.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-05.mmd)
* chapter-06.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-06.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-06.mmd)
* chapter-07.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-07.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-07.mmd)
* chapter-08.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-08.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-08.mmd)
* chapter-09.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-09.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-09.mmd)
* chapter-10.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-10.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-10.mmd)
* chapter-11.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-11.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-11.mmd)
* chapter-12.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-12.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-12.mmd)
* chapter-13.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-13.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-13.mmd)
* chapter-14.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-14.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-14.mmd)
* chapter-15.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-15.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-15.mmd)
* chapter-16.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-16.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-16.mmd)
* chapter-17.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-17.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-17.mmd)
* chapter-18.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-18.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-18.mmd)
* chapter-19.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-19.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-19.mmd)
* chapter-20.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-20.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-20.mmd)
* chapter-21.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-21.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-21.mmd)
* chapter-22.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-22.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-22.mmd)
* chapter-23.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-23.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-23.mmd)
* chapter-24.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-24.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-24.mmd)
* chapter-25.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-25.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-25.mmd)
* chapter-26.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-26.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-26.mmd)
* chapter-27.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-27.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-27.mmd)
* chapter-28.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-28.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-28.mmd)
* chapter-29.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-29.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-29.mmd)
* chapter-30.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-30.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-30.mmd)
* chapter-31.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-31.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-31.mmd)
* chapter-32.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-32.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-32.mmd)
* chapter-33.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-33.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-33.mmd)
* chapter-34.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-34.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-34.mmd)
* chapter-35.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-35.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-35.mmd)
* chapter-36.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-36.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-36.mmd)
* chapter-37.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-37.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-37.mmd)
* chapter-38.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-38.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-38.mmd)
* chapter-39.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-39.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-39.mmd)
* chapter-40.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-40.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-40.mmd)
* chapter-41.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-41.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-41.mmd)
* chapter-42.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-42.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-42.mmd)
* chapter-43.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-43.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-43.mmd)
* chapter-44.mmd
  * [Edit in Mermaid live](https://mermaid.live/edit?code=https://raw.githubusercontent.com/aquesnel/thibault-flowchart/refs/heads/main/flowchart-per-chapter/chapter-44.mmd) | [Save in github](https://github.com/aquesnel/thibault-flowchart/edit/main/flowchart-per-chapter/chapter-44.mmd)


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

