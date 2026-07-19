---
title: "Класс Aspose::Pdf::Annotations::FileAttachmentAnnotation"
linktitle: "FileAttachmentAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Annotations::FileAttachmentAnnotation. Класс описывает аннотацию вложения файла в C++."
type: docs
weight: 3000
url: /ru/cpp/aspose.pdf.annotations/fileattachmentannotation/
---
## FileAttachmentAnnotation class


Класс описывает аннотацию вложения файла.

```cpp
class FileAttachmentAnnotation : public Aspose::Pdf::Annotations::MarkupAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [FileAttachmentAnnotation](./fileattachmentannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::SharedPtr\<FileSpecification\>\&) | Создаёт новую аннотацию FileAttachment на указанной странице. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_File](./get_file/)() | Спецификация файла, связанного с этой аннотацией. |
| [get_Icon](./get_icon/)() | Получает значок, который будет использоваться при отображении аннотации. |
| [get_Opacity](./get_opacity/)() | Получает непрозрачность значка от 0 до 1: 0 — полностью прозрачный, 1 — полностью непрозрачный. |
| [set_File](./set_file/)(const System::SharedPtr\<FileSpecification\>\&) | Спецификация файла, связанного с этой аннотацией. |
| [set_Icon](./set_icon/)(FileIcon) | Устанавливает значок, который будет использоваться при отображении аннотации. |
| [set_Opacity](./set_opacity/)(double) | Устанавливает непрозрачность значка от 0 до 1: 0 — полностью прозрачный, 1 — полностью непрозрачный. |
## См. также

* Class [MarkupAnnotation](../markupannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
