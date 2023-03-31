---
description: Everything you need to know to build and work with spatial tables
---

# Practical tips

This page contains practical information for the following tasks:

* [Assigning vertical labels](practical-tips.md#assigning-vertical-labels)
* [Assigning horizontal labels](practical-tips.md#assigning-horizontal-labels)
* [Working with sticky note and text box data items](practical-tips.md#working-with-sticky-note-and-text-box-data-items)
* [Working with color tags](practical-tips.md#working-with-color-tags)
* [Working with shape tags](practical-tips.md#working-with-shape-tags)
* [Assigning labels to sticky note clusters](practical-tips.md#assigning-labels-to-sticky-note-clusters)
* [Using line connectors](practical-tips.md#using-line-connectors)

### Assigning vertical labels

Vertical labels serve as the foundation for hierarchical categorization within the app. A vertical label is always assigned to a shape and subsequently assigned to data items, such as sticky notes and text boxes, placed within the shape.&#x20;

Nesting shapes with vertical labels within other shapes with vertical labels enables the interpretation of hierarchical relationships.

<figure><img src="../.gitbook/assets/VisualData_tips_nesting_01.png" alt=""><figcaption></figcaption></figure>

#### Assigning vertical labels is a straightforward process, provided that the following guidelines are observed:

1. Vertical labels are always positioned above the shape.
2. They can be placed anywhere along the top margin of the shape, as long as their center points are above the shape.

<figure><img src="../.gitbook/assets/VisualData_tips_verticalLeftRight_01 (1).png" alt=""><figcaption></figcaption></figure>

3. The label must be positioned in close proximity to the shape, with some margin optionally allowed. It is recommended to test the distance between them. Note of the text boxes in the example below will be intepreted correctly as vertical shapes.&#x20;

<figure><img src="../.gitbook/assets/VisualData_tips_verticalNotOK_01.png" alt=""><figcaption></figcaption></figure>

4. Any font size can be used, as long as the above spacing requirements are satisfied.

<figure><img src="../.gitbook/assets/VisualData_tips_verticalFontSize_01 (2).png" alt=""><figcaption></figcaption></figure>

4. Different font colors, bold and italicized fonts, and text backgrounds, as well as text highlighting, are allowed.

<figure><img src="../.gitbook/assets/VisualData_tips_verticalDiffLabels_01.png" alt=""><figcaption></figcaption></figure>

### Assigning horizontal labels

### Working with sticky note and text box data items

Sticky notes and text boxes serve as fundamental data types within Miro's spatial tables. Each sticky note is treated as a distinct data item, while a text box will be interpreted as such unless it is first interpreted as a label.&#x20;

To be associated with a parent category, data items must be contained within its corresponding shape. It is important to note that data items are always associated exclusively with their immediate parent shape, and should not overlap the boundary of the shape. Always select a shape to see its true boundary and ensure proper alignment of data items.

### Working with color tags

The definition of color tags requires the use of a specific vertical category label (e.g., Color tag). This label, along with its associated shape, functions similarly to a map legend, where the different color tag labels will be specified.

Each color tag label is described by a sticky note placed inside the associated shape. The text content of each sticky note represents the label, and the color of the sticky note corresponds to the tag color that will be associated with the label.

{% hint style="info" %}
When defining a vertical label as a color tag legend label, it should be named with one of the following exact strings: "color tags", "colour tags", "Color tags", "Colour tags", "color legend", "colour legend", "Color legend", or "Colour legend".
{% endhint %}

### Working with shape tags

To use shape tags, you need to define a vertical label category that will act as a legend for the shape tag labels. This category label and its associated shape define the area where shape tags and their corresponding labels will be placed.

Each individual shape tag is defined by placing the shape adjacent to the label that it is associated with.&#x20;

{% hint style="info" %}
The category label must have one of the following exact string names: "Shape tags", "Shape Tags", or "shape tags".
{% endhint %}

### Assigning labels to sticky note clusters

A cluster of sticky notes is formed when two or more notes overlap in space. The overlap is determined by the shape of a selected sticky note, which is larger than the note visible on the board when unselected.

&#x20;A cluster will only appear in the results table if it is labeled. To label a cluster, place a text box in close proximity to it. The label should not meet the criteria of a vertical or horizontal label.

### Using line connectors
