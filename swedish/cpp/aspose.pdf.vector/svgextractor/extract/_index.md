---
title: "Aspose::Pdf::Vector::SvgExtractor::Extract metod"
linktitle: "Extrahera"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Vector::SvgExtractor::Extract metod. Extraherar SVG-bild till en sträng från grafiska element som representeras av absorberaren med ett predikatfilter i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.pdf.vector/svgextractor/extract/
---
## SvgExtractor::Extract(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&) method


Extraherar en SVG-bild till en sträng från grafiska element som representeras av [absorber](../) med ett predikatfilter.

```cpp
System::String Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<GraphicsAbsorber> &absorber, System::Predicate<System::SharedPtr<GraphicElement>> filter, const System::SharedPtr<Page> &page)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absorber | const System::SharedPtr\<GraphicsAbsorber\>\& | Det [GraphicsAbsorber](../../graphicsabsorber/) objektet som innehåller de grafiska elementen. |
| filter | System::Predicate\<System::SharedPtr\<GraphicElement\>\> | En predikatfunktion som används för att filtrera de grafiska elementen. |
| sida | const System::SharedPtr\<Page\>\& | Sidan där absorberaren får grafiska element. |

### ReturnValue

Strängen med SVG-innehåll.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsAbsorber](../../graphicsabsorber/)
* Typedef [Predicate](../../../system/predicate/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<GraphicsAbsorber\>\&, System::Predicate\<System::SharedPtr\<GraphicElement\>\>, const System::SharedPtr\<Page\>\&, const System::String\&) method


Extraherar en SVG-bild till en fil från grafiska element som representeras av [absorber](../) med ett predikatfilter.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<GraphicsAbsorber> &absorber, System::Predicate<System::SharedPtr<GraphicElement>> filter, const System::SharedPtr<Page> &page, const System::String &svgFilePath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| absorber | const System::SharedPtr\<GraphicsAbsorber\>\& | Det [GraphicsAbsorber](../../graphicsabsorber/) objektet som innehåller de grafiska elementen. |
| filter | System::Predicate\<System::SharedPtr\<GraphicElement\>\> | En predikatfunktion som används för att filtrera de grafiska elementen. |
| sida | const System::SharedPtr\<Page\>\& | Sidan där absorberaren får grafiska element. |
| svgFilePath | const System::String\& | Målsökvägen för SVG-filen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsAbsorber](../../graphicsabsorber/)
* Typedef [Predicate](../../../system/predicate/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<Page\>\&) method


Extraherar SVG-bilder från en sida till strängar.

```cpp
System::SharedPtr<System::Collections::Generic::List<System::String>> Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<Page> &page)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Page\>\& | Sidan att extrahera. |

### ReturnValue

Listan med SVG-innehållssträngar.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [String](../../../system/string/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<Page\>\&, const System::String\&) method


Extraherar SVG-bilder från en sida till filer.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<Page> &page, const System::String &directory)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | const System::SharedPtr\<Page\>\& | Sidan att extrahera. |
| katalog | const System::String\& | Målkatalogen för att placera SVG-bilder. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&) method


Extraherar grafiska element till en SVG-sträng. Alternativ ignoreras – gruppering, extrahering från rektangel.

```cpp
System::String Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<GraphicElement>>> &elements, const System::SharedPtr<Page> &page)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\& | De grafiska elementen att konvertera. |
| sida | const System::SharedPtr\<Page\>\& | Sidan där absorberaren får grafiska element. |

### ReturnValue

Strängen med SVG-innehåll.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
## SvgExtractor::Extract(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\&, const System::SharedPtr\<Page\>\&, const System::String\&) method


Extraherar grafiska element till en enda SVG-fil. Alternativ ignoreras – gruppering, extrahering från rektangel.

```cpp
void Aspose::Pdf::Vector::SvgExtractor::Extract(const System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<GraphicElement>>> &elements, const System::SharedPtr<Page> &page, const System::String &svgFilePath)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<GraphicElement\>\>\>\& | De grafiska elementen att konvertera. |
| sida | const System::SharedPtr\<Page\>\& | Sidan där absorberaren får grafiska element. |
| svgFilePath | const System::String\& | Målsökvägen för SVG-filen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [GraphicElement](../../graphicelement/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SvgExtractor](../)
* Namespace [Aspose::Pdf::Vector](../../)
* Library [Aspose.PDF for C++](../../../)
