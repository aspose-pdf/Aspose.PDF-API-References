---
title: "Aspose::Pdf::Facades::Form::FillImageField method"
linktitle: "FillImageField"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::Form::FillImageField method. Перегружает функцию FillImageField. Входной параметр — поток изображения в C++."
type: docs
weight: 1000
url: /ru/cpp/aspose.pdf.facades/form/fillimagefield/
---
## Form::FillImageField(const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Перегружает функцию FillImageField. Входные данные — поток изображения.

```cpp
void Aspose::Pdf::Facades::Form::FillImageField(const System::String &fieldName, const System::SharedPtr<System::IO::Stream> &imageStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | const System::String\& | Полностью квалифицированное имя поля. |
| imageStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток изображения. |

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillImageField(const System::String\&, const System::String\&) method


Вставляет изображение в существующее поле кнопки в качестве его внешнего вида согласно полностью квалифицированному имени поля.

```cpp
void Aspose::Pdf::Facades::Form::FillImageField(const System::String &fieldName, const System::String &imageFileName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldName | const System::String\& | Полностью квалифицированное имя поля кнопки изображения. |
| imageFileName | const System::String\& | Путь к файлу изображения, относительный и абсолютный оба допустимы. |

## См. также

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
