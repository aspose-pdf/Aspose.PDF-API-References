---
title: "Aspose::Pdf::Annotations::LinkAnnotation class"
linktitle: "LinkAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::LinkAnnotation class. Представляет гипертекстовую ссылку на пункт назначения в другом месте документа или действие, которое должно быть выполнено в C++."
type: docs
weight: 6000
url: /ru/cpp/aspose.pdf.annotations/linkannotation/
---
## LinkAnnotation class


Представляет либо гипертекстовую ссылку на назначение в другом месте документа, либо действие, которое следует выполнить.

```cpp
class LinkAnnotation : public Aspose::Pdf::Annotations::Annotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [get_Action](./get_action/)() | Действие, которое будет выполнено при активации аннотации ссылки. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_Destination](./get_destination/)() | Пункт назначения, который будет отображён при активации аннотации. |
| [get_Highlighting](./get_highlighting/)() | Визуальный эффект, который будет использоваться, когда кнопка мыши нажата или удерживается внутри её активной области. |
| [LinkAnnotation](./linkannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&) | Создаёт новую аннотацию Link на указанной странице. |
| [set_Action](./set_action/)(const System::SharedPtr\<PdfAction\>\&) | Действие, которое будет выполнено при активации аннотации ссылки. |
| [set_Destination](./set_destination/)(const System::SharedPtr\<IAppointment\>\&) | Пункт назначения, который будет отображён при активации аннотации. |
| [set_Highlighting](./set_highlighting/)(HighlightingMode) | Визуальный эффект, который будет использоваться, когда кнопка мыши нажата или удерживается внутри её активной области. |
## См. также

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
