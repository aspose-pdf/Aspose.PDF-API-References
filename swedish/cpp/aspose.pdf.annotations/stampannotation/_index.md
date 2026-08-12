---
title: "Aspose::Pdf::Annotations::StampAnnotation klass"
linktitle: "StampAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::StampAnnotation klass. Representerar gummistämpelannotation. Denna typ av annotation visar text eller grafik som är avsedd att se ut som om de var stämplade på sidan med en gummistämpel i C++."
type: docs
weight: 10700
url: /sv/cpp/aspose.pdf.annotations/stampannotation/
---
## StampAnnotation class


Representerar gummistämpelannotation. Denna typ av annotation visar text eller grafik som är avsedd att se ut som om den stämplats på sidan med en gummistämpel.

```cpp
class StampAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar [AnnotationSelector](../annotationselector/) besökare när du bläddrar i annoteringssamlingen. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_Icon](./get_icon/)() | Hämtar ikon för gummistämpel. |
| [get_Image](./get_image/)() | Hämtar bild av annotationen. |
| [set_Icon](./set_icon/)(StampIcon) | Ställer in ikon för gummistämpel. |
| [set_Image](./set_image/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställer in bild av annotationen. |
| [StampAnnotation](./stampannotation/)(const System::SharedPtr\<Document\>\&) | Konstruktor. |
| [StampAnnotation](./stampannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Skapar ny [Stamp](../../aspose.pdf/stamp/) annotation på den angivna sidan. |
## Se även

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
