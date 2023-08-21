# Mastering the DOM with JavaScript

My notes learning in depth the DOM and the interaction with it using JS.

### 🟠 What is the DOM?

The DOM stands for `Document Object Model`. It is a programming interface for HTML and XML documents.

The DOM represents the `structure of a document` as a tree-like structure, where each node represents a part of the document (such as an element, attribute, or text).

It allows programs to `dynamically access and manipulate` the content, structure, and style of a document.

### 🟠 Every HTML element has an object in the document hierarchy:

When an HTML document is parsed (is analyzed) by a web browser, it creates a representation of the document as a `DOM tree`. This tree consists of various nodes, with each node representing an HTML element.

Every element in the markup represents a `node` in the Document Object Model (DOM) hierarchy.

Each node in the DOM tree corresponds to `an HTML element, attribute, or text` within the HTML document.

The nodes are organized in a hierarchical structure, where each node has a parent node (except for the root node) and can have zero or more child nodes.

### 🟠 Interacting with the DOM:

The DOM hierarchy allows you to access and manipulate the elements in an HTML document using `JavaScript`.

Each node in the DOM has `properties and methods` that can be used to interact with it, such as changing its content, modifying its attributes, adding or removing child nodes, and more.

Find examples in the html files of this repository.
