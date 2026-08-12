---
title: "Aspose::Pdf::Vector::SvgExtractionOptions klass"
linktitle: "SvgExtractionOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Vector::SvgExtractionOptions klass. Representerar en klass för alternativ för att extrahera vektorgrafik från pdf-dokumentets sida i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class


Representerar en alternativklass för att extrahera vektorgrafik från PDF‑dokumentets sida.

```cpp
class SvgExtractionOptions : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AutoGrouping](./get_autogrouping/)() const | Hämtar och anger alternativet för att automatiskt gruppera subpaths till bilder. Detta alternativ utesluter alternativet [GroupStrength](../). |
| [get_ExtractEverySubPathToSvg](./get_extracteverysubpathtosvg/)() const | Hämtar och anger alternativet för att extrahera varje subpath från ett PDF-dokument till separata SVG-bilder. |
| [get_ExtractionAreaBound](./get_extractionareabound/)() const | Hämtar och anger den begränsningsrektangel som definierar extraktionsområdet för SVG-extraktion. |
| [get_GroupStrength](./get_groupstrength/)() const | Hämtar och anger ett alternativ för styrkan i gruppering av subpaths till bilder. Gör det möjligt att konfigurera graden av gruppering av subpaths. Värdet varierar från 0 till 1. Ett värde på 0 motsvarar att alternativet [ExtractEverySubPathToSvg](../) är aktiverat. Ett värde på 1 skapar en enda bild för alla vektorvägar på sidan. Alternativet har effekt när [AutoGrouping](../) är falskt. Standardvärdet är **0.8**. |
| [get_MinStrokeWidth](./get_minstrokewidth/)() const | Hämtar den minsta linjebredden som kommer att användas i den resulterande SVG:n. Om PDF:en använder en tunnare linjebredd ersätts den med denna bredd. Standardvärdet är 0.5. |
| [get_StrictExtractionAreaBoundCheck](./get_strictextractionareaboundcheck/)() const | Hämtar och anger ett alternativ för att strikt kontrollera om subpaths ligger inom den angivna rektangeln i [ExtractionAreaBound](../). Om den är falsk kommer subpaths som inte är helt inkluderade i [ExtractionAreaBound](../) att extraheras. Standardvärdet är **True**. |
| [get_UnpackPageContentXForm](./get_unpackpagecontentxform/)() const | Hämtar och anger en flagga som bestämmer om XFrom som hittas på sidor ska packas upp eller inte. XFrom-element kan hamna i olika SVG-filer. Endast XForms som renderas av Do‑satser från sidans innehåll packas upp. Inbäddade XForms packas inte upp. |
| [get_UnpackXFormPredicate](./get_unpackxformpredicate/)() const | Hämtar och anger alternativet för att bara packa upp den [XForm](../../aspose.pdf/xform/) som motsvarar det angivna predikatet. |
| [set_AutoGrouping](./set_autogrouping/)(bool) | Hämtar och anger alternativet för att automatiskt gruppera subpaths till bilder. Detta alternativ utesluter alternativet [GroupStrength](../). |
| [set_ExtractEverySubPathToSvg](./set_extracteverysubpathtosvg/)(bool) | Hämtar och anger alternativet för att extrahera varje subpath från ett PDF-dokument till separata SVG-bilder. |
| [set_ExtractionAreaBound](./set_extractionareabound/)(const System::SharedPtr\<Rectangle\>\&) | Hämtar och anger den begränsningsrektangel som definierar extraktionsområdet för SVG-extraktion. |
| [set_GroupStrength](./set_groupstrength/)(double) | Hämtar och anger ett alternativ för styrkan i gruppering av subpaths till bilder. Gör det möjligt att konfigurera graden av gruppering av subpaths. Värdet varierar från 0 till 1. Ett värde på 0 motsvarar att alternativet [ExtractEverySubPathToSvg](../) är aktiverat. Ett värde på 1 skapar en enda bild för alla vektorvägar på sidan. Alternativet har effekt när [AutoGrouping](../) är falskt. Standardvärdet är **0.8**. |
| [set_MinStrokeWidth](./set_minstrokewidth/)(double) | Anger den minsta linjebredden som kommer att användas i den resulterande SVG:n. Om PDF:en använder en tunnare linjebredd ersätts den med denna bredd. Standardvärdet är 0.5. |
| [set_StrictExtractionAreaBoundCheck](./set_strictextractionareaboundcheck/)(bool) | Hämtar och anger ett alternativ för att strikt kontrollera om subpaths ligger inom den angivna rektangeln i [ExtractionAreaBound](../). Om den är falsk kommer subpaths som inte är helt inkluderade i [ExtractionAreaBound](../) att extraheras. Standardvärdet är **True**. |
| [set_UnpackPageContentXForm](./set_unpackpagecontentxform/)(bool) | Hämtar och anger en flagga som bestämmer om XFrom som hittas på sidor ska packas upp eller inte. XFrom-element kan hamna i olika SVG-filer. Endast XForms som renderas av Do‑satser från sidans innehåll packas upp. Inbäddade XForms packas inte upp. |
| [set_UnpackXFormPredicate](./set_unpackxformpredicate/)(System::Predicate\<System::SharedPtr\<XFormPlacement\>\>) | Hämtar och anger alternativet för att bara packa upp den [XForm](../../aspose.pdf/xform/) som motsvarar det angivna predikatet. |
| [SvgExtractionOptions](./svgextractionoptions/)() | Skapar en instans av klassen [SvgExtractionOptions](./). |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
