# svg-us-map
SVG United States map that is ready for javascript manipulation

License: Creative Commons [Attribution-Share Alike 3.0 Unported](https://creativecommons.org/licenses/by-sa/3.0/deed.en)

This a simplified verion of the file with everything nested to make it easier to work with via javascript.\
Original: https://commons.wikimedia.org/wiki/File:Blank_US_Map_With_Labels.svg

Each state (and DC) are nested within a `g` node with the id of the state 2-letter abbreviation.

`<path>` nodes have two classes.\
boundary - The state boundary(s)
label-line - The line between the label and state on small states

`<text>` nodes are the labels.

`<rect>` nodes are the label boxes.
