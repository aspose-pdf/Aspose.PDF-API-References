---
title: "Aspose::Pdf::Annotations::PopupAnnotation-klass"
linktitle: "PopupAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::PopupAnnotation-klass. Representerar popup-annotation som visar text i ett popup-fönster för inmatning och redigering i C++."
type: docs
weight: 8800
url: /sv/cpp/aspose.pdf.annotations/popupannotation/
---
## PopupAnnotation class


Representerar pop-up-anteckningen som visar text i ett pop-up-fönster för inmatning och redigering.

```cpp
class PopupAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar besökarobjekt för att bearbeta anteckningen. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_Open](./get_open/)() | Hämtar en flagga som anger om popup-annotation ska visas öppen från början. |
| [get_Parent](./get_parent/)() | Hämtar föräldraannotation som denna popup-annotation ska vara associerad med. Om denna post finns, ska föräldraannotationens Innehåll, M, C och T‑poster åsidosätta de för popup-annotationens egna. |
| [PopupAnnotation](./popupannotation/)(const System::SharedPtr\<Document\>\&) | Konstruktor. för användning i Generator. |
| [PopupAnnotation](./popupannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Skapar ny popup-annotation på den angivna sidan. |
| [set_Open](./set_open/)(bool) | Ställer in en flagga som anger om popup-annotation ska visas öppen från början. |
| [set_Parent](./set_parent/)(const System::SharedPtr\<Annotation\>\&) | Ställer in föräldraannotation som denna popup-annotation ska vara associerad med. Om denna post finns, ska föräldraannotationens Innehåll, M, C och T‑poster åsidosätta de för popup-annotationens egna. |
## Se även

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
