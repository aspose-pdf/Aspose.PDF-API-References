---
title: com.aspose.pdf.vector
linktitle: com.aspose.pdf.vector
second_title: Aspose.PDF for Java API Reference
description: The Aspose.Pdf.Vector is a root namespace for graphics operations.
type: docs
weight: 390
url: /java/com.aspose.pdf.vector/
---
The Aspose.Pdf.Vector is a root namespace for graphics operations.

## Classes

| Class | Description |
| --- | --- |
| [GraphicElement](./graphicelement/) | Represents base class for graphics object on the page. |
| [GraphicElementCollection](./graphicelementcollection/) | Represents {@link GraphicElement} collection. |
| [GraphicsAbsorber](./graphicsabsorber/) | Represents an absorber object of graphics elements. Performs graphics search and provides access to search results via {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}) collection. |
| [GraphicState](./graphicstate/) | Represents graphic state of the current {@link GraphicElement}. |
| [InternalHelper](./internalhelper/) |  |
| [SubPath](./subpath/) | Represents vector graphics object on the page. Basically, vector graphics objects are represented by two groups of SubPaths. One of them is represented by a set of lines and curves. Others are presented as rectangles and can sometimes be confused. Usually it is a rectangular area that has a color, but very often this rectangle is placed at the beginning of the page and defines the entire space of the page in white. So you get the SubPath, but visually you only see the text on the page. |
| [XFormPlacement](./xformplacement/) | Represents XForm placement. If the XForm is displayed on the page more than 1 time, all XformPlacements associated with this XForm will have common graphical elements, but different graphical states. |
