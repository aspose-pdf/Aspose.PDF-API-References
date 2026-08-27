---
title: "com.aspose.pdf.vector"
linktitle: "com.aspose.pdf.vector"
second_title: "Aspose.PDF för Java API-referens"
description: "Aspose.Pdf.Vector är ett rot-namnrymd för grafikoperationer."
type: docs
weight: 390
url: /sv/java/com.aspose.pdf.vector/
---
Aspose.Pdf.Vector är ett rot-namnrymd för grafikoperationer.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [GraphicElement](./graphicelement/) | Representerar basklass för grafiskt objekt på sidan. |
| [GraphicElementCollection](./graphicelementcollection/) | Representerar {@link GraphicElement}-samling. |
| [GraphicsAbsorber](./graphicsabsorber/) | Representerar ett absorberingsobjekt för grafikelement. Utför grafiksökning och ger åtkomst till sökresultat via {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements})-samlingen. |
| [GraphicState](./graphicstate/) | Representerar grafiskt tillstånd för den aktuella {@link GraphicElement}. |
| [InternalHelper](./internalhelper/) |  |
| [SubPath](./subpath/) | Representerar ett vektorgrafikobjekt på sidan. I grund och botten representeras vektorgrafikobjekt av två grupper av SubPaths. En av dem representeras av en uppsättning linjer och kurvor. De andra presenteras som rektanglar och kan ibland förväxlas. Vanligtvis är det ett rektangulärt område som har en färg, men mycket ofta placeras denna rektangel i början av sidan och definierar hela sidans utrymme i vitt. Så du får SubPath, men visuellt ser du bara texten på sidan. |
| [XFormPlacement](./xformplacement/) | Representerar XForm-placering. Om XForm visas på sidan mer än en gång, kommer alla XformPlacements som är associerade med detta XForm att ha gemensamma grafiska element, men olika grafiska tillstånd. |
