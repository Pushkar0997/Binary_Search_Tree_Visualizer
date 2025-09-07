# Binary_Search_Tree_Visualizer
🌳 Interactive Binary Search Tree (BST) Visualizer
A single-file, fully interactive web application built with vanilla HTML, CSS, and JavaScript to visualize the core operations of a Binary Search Tree. This educational tool provides clear, step-by-step animations for insertion, deletion, searching, and various tree traversal algorithms.

➡️ Live Demo Link (Deploy on GitHub Pages!)

✨ Features
Node Operations:

Insert: Animate the process of finding the correct position and adding a new node.

Delete: Visually handle all three deletion cases (leaf node, one child, two children), including finding the in-order successor.

Search: Show the path taken to find a specific node or determine its absence.

Tree Traversals:

In-order

Pre-order

Post-order

Level-order

Interactive Controls:

Animation Speed: A slider to control the speed of all visualizations for better understanding.

Reset: Instantly clear the tree to start fresh.

Responsive Design: A clean, modern, and dark-themed UI that adapts seamlessly to all screen sizes, from mobile devices to desktops.

Real-time Feedback: A status bar provides clear messages for every operation, success, or error.

🛠️ Tech Stack
HTML5: For the core structure and layout.

CSS3 / Tailwind CSS: For a utility-first, responsive, and modern design.

JavaScript (ES6+): For all the logic, including the BST data structure, canvas rendering, and animation engine.

HTML5 Canvas API: Used for drawing the tree nodes, edges, and handling all visual rendering.

🚀 How to Run Locally
This project is a single, self-contained HTML file with no external dependencies (other than the Tailwind CSS CDN).

Clone the repository:

git clone [https://github.com/your-github-username/your-repo-name.git](https://github.com/your-github-username/your-repo-name.git)

Navigate to the directory:

cd your-repo-name

Open the file:

Simply open the bst-visualizer.html file in any modern web browser like Chrome, Firefox, or Edge.

🧠 Core Concepts & Code Structure
The JavaScript code is logically separated into two main parts to distinguish the data structure from its visual representation.

Data Structure Logic (BinarySearchTree and Node classes):

Node: A simple class to represent each node with a value, left child, and right child.

BinarySearchTree: Encapsulates all the core BST algorithms (insert, delete, _findMinNode, search). This class has no knowledge of the UI or canvas, making the logic pure and reusable.

Visualizer & Animation Logic:

Canvas Rendering: A set of functions (drawNode, drawEdge, drawTree, updateNodePositions) that use the HTML5 Canvas API to render the tree's current state.

Animation Engine: The async/await syntax combined with a sleep() utility is used to create smooth, easy-to-read, and non-blocking animations for all operations. This avoids complex callback structures.

DOM Manipulation: Standard event listeners connect the UI controls (buttons, inputs) to the handler functions that trigger the animations and update the status bar.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
