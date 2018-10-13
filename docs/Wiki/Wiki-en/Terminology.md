> Introduction / Terminology

Some keyword specific to *papoGen.css*

---
## 1. Types of Components

*papoGen.css* classifies components into different definition types. Each of these four types uses a unique definition format.

| Types | Description |
|---|---|
| *Globals* | *Globals* are styles that are applied across a site, including CSS resets, and sitewide font, sizing defaults, etc.. Notice that *globals* include site-wide theming variables can be inherited and modified by other components. |
| *Layouts* | *Layouts* are used for defining the layout in a page. |
| *Elements* | *Elements* are page elements with a single function which can exist alone or in a plural form with elements sharing qualities. |
| *Displays* | *Displays* are for presenting specific types of content that is usually consistent across a page. | 
| *Modules* | *Modules* are components that include both a definition of how they appear and how they behave. Besides, *modules* are heterogeneous groups of components which are usually found together. |

---
## 2. Definition Terminology

These parts of a definition are consistent across definitions and are common patterns for describing components. 

| Terminology | Description |
|---|---|
| *Types* | *Types* are categories of an element that modified the element's standard appearance. *Types* cannot be used simultaneously on the same element. |
| *Content* | *Content* are parts which only have meaning in the context of a component. Content use names which describe the type of expected content. |
| *Variations* | *Variations* modify variables of an element (e.g., size or color). *Variations* are mutually inclusive which can be used together to modify an element. |
| *States* | *States* are modifications to an element that help indicate a change in state.  |