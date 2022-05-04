# SplayTreeVisualizer
Splay Tree Visualizer for ADS innovative assignment 

<!-- PROJECT LOGO -->
<p align="center">
 

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#About-The-Project">About The Project</a></li>
    <li><a href="#Features">Features</a></li>
    <li><a href="#Prerequisites">Prerequisites</a></li>
    <li><a href="#Usage">Usage</a></li>
    <li><a href="#GroupDetails">Contacts</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About-The-Project

The visualization is done with standard HTML, CSS, and JavaScript along with the Bootstrap CSS framework and D3.js for visualizer.


## Features
 
- Add key
- Delete key
- Search key
- Find min
- Find max

## Prerequisites
- HTML,CSS,Javascript
- D3.js library for visualization
- Bootstrap
  
## Usage
•	Add
-	Add a key value in its respective field. 
-	After which a node will be generated and the tree will be splayed accordingly.
-	After splaying, the new node will become the root node.

•	Remove
-	After adding, the nodes can also be removed by giving the key value in the “Remove” field.
-	After removal, the maximum key that is less than the removed key will become the root.
-	If the desired key is not found for removal, the tree will splay around the nearest value to that key.

•	Find
-	We can also search for a key by entering its value in the “Find” field.
-	If the key is found, then the tree will splay around that key.
-	If the key is not found, then the minimum node from the right subtree will become the new root.

•	Max
-	The Max button will highlight the maximum element in the tree.

•	Min
-	The Min button will highlight the minimum element in the tree.
  
  
## GroupDetails

Jeel Patel - 19BCE179

Jeel Patel - 19BCE180
  
Krupal Patel - 19BCE186
