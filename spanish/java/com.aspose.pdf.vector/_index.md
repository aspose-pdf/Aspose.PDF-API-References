---
title: "com.aspose.pdf.vector"
linktitle: "com.aspose.pdf.vector"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El Aspose.Pdf.Vector es un espacio de nombres raíz para operaciones gráficas."
type: docs
weight: 390
url: /es/java/com.aspose.pdf.vector/
---
El Aspose.Pdf.Vector es un espacio de nombres raíz para operaciones gráficas.

## Clases

| Clase | Descripción |
| --- | --- |
| [GraphicElement](./graphicelement/) | Representa la clase base para el objeto gráfico en la página. |
| [GraphicElementCollection](./graphicelementcollection/) | Representa la colección {@link GraphicElement}. |
| [GraphicsAbsorber](./graphicsabsorber/) | Representa un objeto absorbente de elementos gráficos. Realiza la búsqueda de gráficos y proporciona acceso a los resultados de la búsqueda a través de la colección {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}). |
| [GraphicState](./graphicstate/) | Representa el estado gráfico del {@link GraphicElement} actual. |
| [InternalHelper](./internalhelper/) |  |
| [SubPath](./subpath/) | Representa un objeto de gráficos vectoriales en la página. Básicamente, los objetos de gráficos vectoriales se representan mediante dos grupos de SubPaths. Uno de ellos está representado por un conjunto de líneas y curvas. Los demás se presentan como rectángulos y a veces pueden confundirse. Normalmente es un área rectangular que tiene un color, pero con frecuencia este rectángulo se coloca al inicio de la página y define todo el espacio de la página en blanco. Así que obtienes el SubPath, pero visualmente solo ves el texto en la página. |
| [XFormPlacement](./xformplacement/) | Representa la ubicación del XForm. Si el XForm se muestra en la página más de una vez, todas las XformPlacements asociadas con este XForm tendrán elementos gráficos comunes, pero estados gráficos diferentes. |
