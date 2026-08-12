---
title: "Aspose::Pdf::Annotations::FileAttachmentAnnotation-klass"
linktitle: "FileAttachmentAnnotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::FileAttachmentAnnotation-klass. Klassen beskriver en filbilaggsanteckning i C++."
type: docs
weight: 3000
url: /sv/cpp/aspose.pdf.annotations/fileattachmentannotation/
---
## FileAttachmentAnnotation class


Klass som beskriver filbilags‑annotation.

```cpp
class FileAttachmentAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepterar ett besökarobjekt för att bearbeta anteckningen. |
| [FileAttachmentAnnotation](./fileattachmentannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<FileSpecification\>\&) | Skapar en ny filbilaggsanteckning på den angivna sidan. |
| [get_AnnotationType](./get_annotationtype/)() override | Hämtar typ av annotation. |
| [get_File](./get_file/)() | Specifikationen av filen som är associerad med denna anteckning. |
| [get_Icon](./get_icon/)() | Hämtar ikonen som ska användas vid visning av anteckningen. |
| [get_Opacity](./get_opacity/)() | Hämtar ikonens opacitet från 0 till 1: 0 - helt genomskinlig, 1 - helt ogenomskinlig. |
| [set_File](./set_file/)(const System::SharedPtr\<FileSpecification\>\&) | Specifikationen av filen som är associerad med denna anteckning. |
| [set_Icon](./set_icon/)(FileIcon) | Ställer in ikonen som ska användas vid visning av anteckningen. |
| [set_Opacity](./set_opacity/)(double) | Ställer in ikonens opacitet från 0 till 1: 0 - helt genomskinlig, 1 - helt ogenomskinlig. |
## Se även

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
