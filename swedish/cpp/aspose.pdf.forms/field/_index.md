---
title: "Klassen Aspose::Pdf::Forms::Field"
linktitle: "Fält"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Forms::Field-klass. Basisklass för acro-formulärfält i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.pdf.forms/field/
---
## Field class


Basklass för acro-formulärfält.

```cpp
class Field : public Aspose::Pdf::Annotations::WidgetAnnotation,
              public System::Collections::Generic::ICollection<System::SharedPtr<Annotations::WidgetAnnotation>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CopyTo](./copyto/)(const System::ArrayPtr\<System::SharedPtr\<Field\>\>\&, int32_t) | Kopierar underfält från detta fält till en array med start från angivet index. |
| [CopyToWidgetArray](./copytowidgetarray/)(const System::ArrayPtr\<System::SharedPtr\<Annotations::WidgetAnnotation\>\>\&, int32_t) | Kopierar underfält från detta fält till en array med start från angivet index. |
| [ExecuteFieldJavaScript](./executefieldjavascript/)(const System::SharedPtr\<Annotations::JavascriptAction\>\&) | Utför en specificerad JavaScript‑åtgärd för fältet. |
| [Field](./field/)(const System::SharedPtr\<Document\>\&) | Skapar fält för användning i Generator. |
| [Flatten](./flatten/)() override | Tar bort detta fält och placerar dess värde direkt på sidan. |
| [get_AlternateName](./get_alternatename/)() | Hämtar alternativt namn för fältet (Ett alternativt fältnamn som ska användas i stället för det faktiska fältnamnet där fältet identifieras i användargränssnittet). Alternativt namn används som verktygstips för fältet i Adobe Acrobat. |
| [get_AnnotationIndex](./get_annotationindex/)() | Hämtar index för denna annotation på sidan. |
| [get_Count](./get_count/)() const override | Hämtar antalet underfält i detta fält. (Till exempel antalet objekt i ett radioknappsfält). |
| static [get_FitIntoRectangle](./get_fitintorectangle/)() | Om true så minskas teckenstorleken för att passa texten i den angivna rektangeln. |
| [get_IsGroup](./get_isgroup/)() const | Hämtar booleskt värde som indikerar om detta fält är ett icke‑terminalt fält, dvs. en grupp av fält. |
| [get_IsSharedField](./get_issharedfield/)() const | Egenskap för Generator‑stöd. Används när fältet läggs till i sidhuvud eller sidfot. Om true skapas detta fält en gång och dess utseende visas på alla dokumentets sidor. Om false skapas ett separat fält för varje dokumentsida. |
| [get_IsSynchronized](./get_issynchronized/)() | Returnerar true om ordboken är synkroniserad. |
| [get_MappingName](./get_mappingname/)() | Hämtar mappningsnamnet för fältet som ska användas vid export av interaktiva formulärfältdata från dokumentet. |
| static [get_MaxFontSize](./get_maxfontsize/)() | Maximal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| static [get_MinFontSize](./get_minfontsize/)() | Minimal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| [get_PageIndex](./get_pageindex/)() override | Hämtar sidans index som innehåller detta fält. |
| [get_PartialName](./get_partialname/)() | Hämtar delnamnet för fältet. |
| [get_Rect](./get_rect/)() override | Hämtar fältets rektangel. |
| [get_SyncRoot](./get_syncroot/)() const | Synkroniseringsobjekt. |
| [get_TabOrder](./get_taborder/)() | Hämtar tabbordning för fältet. |
| virtual [get_Value](./get_value/)() | Hämtar värdet på fältet. |
| [GetEnumerator](./getenumerator/)() override | Returnerar enumerator för innehållna fält. |
| [idx_get](./idx_get/)(const System::String\&) | Hämtar delfält som finns i detta fält enligt delfältets namn. |
| [idx_get](./idx_get/)(int32_t) | Hämtar delfält som finns i detta fält enligt index. |
| [Recalculate](./recalculate/)() | Beräknar om alla beräknade fält i formuläret. |
| [set_AlternateName](./set_alternatename/)(const System::String\&) | Ställer in alternativt namn för fältet (Ett alternativt fältnamn som ska användas i stället för det faktiska fältnamnet där fältet identifieras i användargränssnittet). Alternativt namn används som verktygstips för fältet i Adobe Acrobat. |
| [set_AnnotationIndex](./set_annotationindex/)(int32_t) | Ställer in index för denna annotation på sidan. |
| static [set_FitIntoRectangle](./set_fitintorectangle/)(bool) | Om true så minskas teckenstorleken för att passa texten i den angivna rektangeln. |
| [set_IsSharedField](./set_issharedfield/)(bool) | Egenskap för Generator‑stöd. Används när fältet läggs till i sidhuvud eller sidfot. Om true skapas detta fält en gång och dess utseende visas på alla dokumentets sidor. Om false skapas ett separat fält för varje dokumentsida. |
| [set_MappingName](./set_mappingname/)(const System::String\&) | Ställer in mappningsnamnet för fältet som ska användas vid export av interaktiva formulärfältdata från dokumentet. |
| static [set_MaxFontSize](./set_maxfontsize/)(double) | Maximal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| static [set_MinFontSize](./set_minfontsize/)(double) | Minimal teckenstorlek som kan användas för fältinnehåll. -1 för att inte kontrollera storlek. |
| [set_PartialName](./set_partialname/)(const System::String\&) | Ställer in delnamnet för fältet. |
| [set_Rect](./set_rect/)(System::SharedPtr\<Rectangle\>) override | Ställer in fältets rektangel. |
| [set_TabOrder](./set_taborder/)(int32_t) | Ställer in tabbordning för fältet. |
| virtual [set_Value](./set_value/)(System::String) | Ställer in värdet på fältet. |
| virtual [SetPosition](./setposition/)(System::SharedPtr\<Point\>) | Ställ in position för fältet. |
## Se även

* Class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
