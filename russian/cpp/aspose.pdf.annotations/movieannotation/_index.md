---
title: "Aspose::Pdf::Annotations::MovieAnnotation класс"
linktitle: "MovieAnnotation"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::MovieAnnotation класс. Представляет аннотацию фильма, содержащую анимированную графику и звук, которые отображаются на экране компьютера и через динамики. Когда аннотация активируется, фильм воспроизводится в C++."
type: docs
weight: 6700
url: /ru/cpp/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class


Представляет аннотацию фильма, содержащую анимированную графику и звук, которые отображаются на экране компьютера и воспроизводятся через динамики. При активации аннотации фильм воспроизводится.

```cpp
class MovieAnnotation : public Aspose::Pdf::Annotations::Annotation,
                        public Aspose::Pdf::Annotations::Annotation::ITitledAnnotation
```

## Методы

| Метод | Описание |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Принимает объект‑посетитель для обработки аннотации. |
| [get_AnnotationType](./get_annotationtype/)() override | Получает тип аннотации. |
| [get_Aspect](./get_aspect/)() | Получает ширину и высоту ограничивающего прямоугольника фильма в пикселях. |
| [get_File](./get_file/)() | Получает спецификацию файла, идентифицирующую самодокументирующийся файл фильма. |
| [get_Poster](./get_poster/)() | Получает флаг или поток, указывающий, будет ли и как отображаться постер-изображение, представляющее фильм. Если true, постер будет получен из файла фильма; если false, постер отображаться не будет. |
| [get_Rotate](./get_rotate/)() | Получает количество градусов, на которое фильм должен быть повернут по часовой стрелке относительно страницы. Значение должно быть кратным 90. |
| [get_Title](./get_title/)() override | Получает заголовок аннотации фильма. |
| [MovieAnnotation](./movieannotation/)(const System::SharedPtr\<Document\>\&, const System::String\&) | Конструктор для использования с Generator. |
| [MovieAnnotation](./movieannotation/)(const System::SharedPtr\<Aspose::Pdf::Page\>\&, const System::SharedPtr\<Rectangle\>\&, const System::String\&) | Создаёт новую звуковую аннотацию на указанной странице. |
| [set_Aspect](./set_aspect/)(const System::SharedPtr\<Point\>\&) | Устанавливает ширину и высоту ограничивающего прямоугольника фильма в пикселях. |
| [set_File](./set_file/)(const System::SharedPtr\<FileSpecification\>\&) | Устанавливает спецификацию файла, идентифицирующую самодокументирующийся файл фильма. |
| [set_Poster](./set_poster/)(bool) | Устанавливает флаг или поток, указывающий, будет ли и как отображаться постер-изображение, представляющее фильм. Если true, постер будет получен из файла фильма; если false, постер отображаться не будет. |
| [set_Rotate](./set_rotate/)(int32_t) | Устанавливает количество градусов, на которое фильм должен быть повернут по часовой стрелке относительно страницы. Значение должно быть кратным 90. |
| [set_Title](./set_title/)(System::String) override | Устанавливает заголовок аннотации фильма. |
## См. также

* Class [Annotation](../annotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
