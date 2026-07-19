---
title: "Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo метод"
linktitle: "CopyTo"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo method. Копирует элементы словаря в массив, начиная с указанного индекса массива в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.annotations/appearancedictionary/copyto/
---
## AppearanceDictionary::CopyTo(const System::ArrayPtr\<System::SharedPtr\<XForm\>\>\&, int32_t) method


Копирует элементы словаря в массив, начиная с указанного индекса массива.

```cpp
void Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo(const System::ArrayPtr<System::SharedPtr<XForm>> &array, int32_t index)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | const System::ArrayPtr\<System::SharedPtr\<XForm\>\>\& | Массив, в который должны быть скопированы элементы. |
| индекс | int32_t | Индекс, в который должны быть скопированы элементы. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## AppearanceDictionary::CopyTo(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\>, int32_t) method


Копирует элементы ICollection в массив, начиная с указанного индекса массива.

```cpp
void Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo(System::ArrayPtr<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XForm>>> array, int32_t arrayIndex) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\> | Одномерный Array, который является получателем элементов, скопированных из ICollection. Array должен иметь нулевую базу индексации. |
| arrayIndex | int32_t | Нулевой индекс в массиве, с которого начинается копирование. |
## Примечания



Проверка границ не выполняется.
## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
