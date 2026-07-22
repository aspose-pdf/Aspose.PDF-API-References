---
title: "Klassen Aspose::Pdf::Vector::SvgExtractor"
linktitle: "SvgExtractor"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Vector::SvgExtractor-klass. Representerar en klass för extrahering av SVG-bilder från en sida i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.pdf.vector/svgextractor/
---
## SvgExtractor class


Representerar en klass för extraktion av SVG‑bilder från sidan.

```cpp
class SvgExtractor : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Extract](./extract/)(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&) | Extraherar en SVG-bild till en sträng från grafiska element som representeras av [absorber](../) med ett predikatfilter. |
| [Extract](./extract/)(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&, const System::String\&) | Extraherar en SVG-bild till en fil från grafiska element som representeras av [absorber](../) med ett predikatfilter. |
| [Extract](./extract/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&) | Extraherar grafiska element till en SVG-sträng. Alternativ ignoreras – gruppering, extrahering från rektangel. |
| [Extract](./extract/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) | Extraherar grafiska element till en enda SVG-fil. Alternativ ignoreras – gruppering, extrahering från rektangel. |
| [Extract](./extract/)(const System::SharedPtr\<Page\>\&) | Extraherar SVG-bilder från en sida till strängar. |
| [Extract](./extract/)(const System::SharedPtr\<Page\>\&, const System::String\&) | Extraherar SVG-bilder från en sida till filer. |
| [SvgExtractor](./svgextractor/)() | Representerar en klass för att extrahera SVG-bilder från en sida. |
| [SvgExtractor](./svgextractor/)(const System::SharedPtr\<SvgExtractionOptions\>\&) | Representerar en klass för att extrahera SVG-bilder från en sida. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
