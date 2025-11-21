---
title: Aspose::Pdf::Vector namespace
linktitle: Aspose::Pdf::Vector
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector namespace. The Aspose.Pdf.Vector is a root namespace for graphics operations in C++.'
type: docs
weight: 2600
url: /cpp/aspose.pdf.vector/
---

The **[Aspose.Pdf.Vector](./)** is a root namespace for graphics operations.

## Classes

| Class | Description |
| --- | --- |
| [GraphicElement](./graphicelement/) | Represents base class for graphics object on the page. |
| [GraphicElementCollection](./graphicelementcollection/) | Represents [GraphicElement](./graphicelement/) collection. |
| [GraphicsAbsorber](./graphicsabsorber/) | Represents an absorber object of graphics elements. Performs graphics search and provides access to search results via [GraphicsAbsorber::Elements](../) collection. |
| [GraphicState](./graphicstate/) | Represents graphic state of the current [GraphicElement](./graphicelement/). |
| [SubPath](./subpath/) | Represents vector graphics object on the page. Basically, vector graphics objects are represented by two groups of SubPaths. One of them is represented by a set of lines and curves. Others are presented as rectangles and can sometimes be confused. Usually it is a rectangular area that has a color, but very often this rectangle is placed at the beginning of the page and defines the entire space of the page in white. So you get the [SubPath](./subpath/), but visually you only see the text on the page. |
| [SubPathGroup](./subpathgroup/) | Represents a class for a group of graphic element containers. Class objects have a bounding box to account for group size. |
| [SvgExtractionOptions](./svgextractionoptions/) | Represents an options class for extracting vector graphics from the pdf document page. |
| [SvgExtractor](./svgextractor/) | Represents a class to SVG-images extraction from page. |
| [XFormPlacement](./xformplacement/) | Represents [XForm](../aspose.pdf/xform/) placement. If the [XForm](../aspose.pdf/xform/) is displayed on the page more than 1 time, all XformPlacements associated with this [XForm](../aspose.pdf/xform/) will have common graphical elements, but different graphical states. |
