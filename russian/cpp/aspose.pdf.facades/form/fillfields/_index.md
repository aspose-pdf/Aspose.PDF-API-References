---
title: "Метод Aspose::Pdf::Facades::Form::FillFields"
linktitle: "FillFields"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::Form::FillFields. Заполняет поля текстовых коробок текстовыми значениями и сохраняет документ. Актуально для подписанных документов. Примечание: применяется только к Text Box. И имена, и значения полей чувствительны к регистру в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf.facades/form/fillfields/
---
## Form::FillFields method


Заполняет поля текстовых коробок текстовыми значениями и сохраняет документ. Актуально для подписанных документов. Примечание: применяется только к [Text](../../../aspose.pdf.text/) Box. И имена, и значения полей чувствительны к регистру.

```cpp
bool Aspose::Pdf::Facades::Form::FillFields(const System::ArrayPtr<System::String> &fieldNames, const System::ArrayPtr<System::String> &fieldValues, System::SharedPtr<System::IO::Stream> &output)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| fieldNames | const System::ArrayPtr\<System::String\>\& | Имена полей. |
| fieldValues | const System::ArrayPtr\<System::String\>\& | Новые значения полей. |
| output | System::SharedPtr\<System::IO::Stream\>\& | Поток, в который будет сохранён документ. |

### ReturnValue

true, если поле найдено и успешно заполнено.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
