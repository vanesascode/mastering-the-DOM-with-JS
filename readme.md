# Mastering the DOM with JavaScript

My notes learning in depth the DOM and the interaction with it using JS.

---

### 🟠 What is the DOM?

The DOM stands for `Document Object Model`. It is a programming interface for HTML and XML documents.

The DOM represents the `structure of a document` as a tree-like structure, where each node represents a part of the document (such as an element, attribute, or text).

It allows programs to `dynamically access and manipulate` the content, structure, and style of a document.

---

### 🟠 Every HTML element has an object in the document hierarchy:

When an HTML document is parsed (is analyzed) by a web browser, it creates a representation of the document as a `DOM tree`. This tree consists of various nodes, with each node representing an HTML element.

Every element in the markup represents a `node` in the Document Object Model (DOM) hierarchy.

Each node in the DOM tree corresponds to `an HTML element, attribute, or text` within the HTML document.

The nodes are organized in a hierarchical structure, where each node has a parent node (except for the root node) and can have zero or more child nodes.

---

### 🟠 Interacting with the DOM:

The DOM hierarchy allows you to access and manipulate the elements in an HTML document using `JavaScript`.

Each node in the DOM has `properties and methods` that can be used to interact with it, such as changing its content, modifying its attributes, adding or removing child nodes, and more.

Find examples in the html files of this repository.

---

### 🟠 Access different nodes and their relationships within the document structure:

1.  `parentElement` : This property is similar to `parentNode` and returns the parent element of a specified element node. It is often used interchangeably with parentNode .

2.  `nextSibling` : This property returns the next sibling node of the specified node. It can be any type of node, including elements, text nodes, comments, etc.

3.  `previousSibling` : This property returns the previous sibling node of the specified node. Like nextSibling , it can be any type of node.

4.  `childNodes` : This property returns a collection of all child nodes of the specified node, including elements, text nodes, comments, etc.

5.  `firstChild` : This property returns the first child node of the specified node.

6.  `lastChild` : This property returns the last child node of the specified node.
