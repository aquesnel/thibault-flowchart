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

 
# How to Edit a flowchart

## GUI editing and live text preview

* open a browser to one of the GUI editors (eg. https://www.mermaidflow.app/editor )
* Copy/paste the text of an `.mmd` mermaid file into the text area
* Edit the flowchart
* Copy/paste the text from the text area into an `.mmd` mermaid file

## Quick edit links

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

