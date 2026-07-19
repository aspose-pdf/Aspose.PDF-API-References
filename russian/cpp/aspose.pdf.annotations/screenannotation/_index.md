---
title: "Aspose::Pdf::Annotations::ScreenAnnotation класс"
linktitle: "ScreenAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::ScreenAnnotation класс. Экранная аннотация, указывающая область страницы, на которой могут воспроизводиться медиа‑клипы на C++."
type: docs
weight: 9800
url: /ru/cpp/aspose.pdf.annotations/screenannotation/
---
## ScreenAnnotation class


Экранная аннотация, указывающая область страницы, на которой могут воспроизводиться медиа‑клипы.

```cpp
class ScreenAnnotation : public Aspose::Pdf::Annotations::Annotation,
                         public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [get_Action](./get_action/)() | Получает действие, которое будет выполнено при активации аннотации. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_Title](./get_title/)() override | Получает заголовок экранной аннотации. |
| [ScreenAnnotation](./screenannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) | Создаёт новую экранную аннотацию на указанной странице. |
| [set_Title](./set_title/)(System::String) override | Устанавливает заголовок экранной аннотации. |
## См. также

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
