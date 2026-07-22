---
title: "Aspose::Pdf::ImagePlacementAbsorber class"
linktitle: "ImagePlacementAbsorber"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::ImagePlacementAbsorber class. Representerar ett absorberande objekt för bildplaceringsobjekt. Utför sökning av bildanvändningar och ger åtkomst till sökresultaten via ImagePlacementAbsorber::ImagePlacements‑samlingen i C++."
type: docs
weight: 8100
url: /sv/cpp/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class


Representerar ett absorberande objekt för bildplaceringsobjekt. Utför sökning efter bildanvändningar och ger åtkomst till sökresultaten via samlingen [ImagePlacementAbsorber::ImagePlacements](../).

```cpp
class ImagePlacementAbsorber : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_ImagePlacements](./get_imageplacements/)() const | Hämtar samling av bildplaceringsförekomster som presenteras med [ImagePlacement](../imageplacement/)‑objekt. |
| [get_IsReadOnlyMode](./get_isreadonlymode/)() const | Hämtar/ställer in skrivskyddat läge för parsingsoperationssamlingen. Det kan hjälpa mot minnesutrymmes‑undantag. |
| [ImagePlacementAbsorber](./imageplacementabsorber/)() | Initierar en ny instans av [ImagePlacementAbsorber](./)‑objektet. |
| [set_IsReadOnlyMode](./set_isreadonlymode/)(bool) | Hämtar/ställer in skrivskyddat läge för parsingsoperationssamlingen. Det kan hjälpa mot minnesutrymmes‑undantag. |
| [Visit](./visit/)(const System::SharedPtr\<Page\>\&) | Utför sökning på den angivna sidan. |
| [Visit](./visit/)(const System::SharedPtr\<Document\>\&) | Utför sökning i det angivna dokumentet. |
## Anmärkningar


Objektet [ImagePlacementAbsorber](./) används i huvudsak i bildsökning‑scenario. När sökningen är klar representeras förekomsterna med [ImagePlacement](../imageplacement/)‑objekt som samlingen [ImagePlacementAbsorber::ImagePlacements](../) innehåller. Objektet [ImagePlacement](../imageplacement/) ger åtkomst till bildplacerings‑egenskaperna: dimensioner, upplösning osv. [Image](../image/) positiv rotation är moturs, för sidan är den medurs. Här måste vi representera bildens rotationsvinkel, så vi drar av sidans vinkel från bildens vinkel.
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
