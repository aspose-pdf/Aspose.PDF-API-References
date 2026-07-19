---
title: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_get метод"
linktitle: "idx_get"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_get method. Представляет удобную форму получения потоков отображения в C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.pdf.annotations/appearancedictionary/idx_get/
---
## AppearanceDictionary::idx_get method


Представляет удобную форму для получения потоков внешнего вида.

```cpp
System::SharedPtr<XForm> Aspose::Pdf::Annotations::AppearanceDictionary::idx_get(const System::String &key) const override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| key | const System::String\& | Представляет путь к потоку отображения. Если словарь отображения имеет подсловарии, то путь должен содержать 2 части ([Keys](../)), иначе путь состоит только из одной части. |

### ReturnValue

[XForm](../../../aspose.pdf/xform/) object (appearance stream) which corresponds to the given key.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [String](../../../system/string/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
