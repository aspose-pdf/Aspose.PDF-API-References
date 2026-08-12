---
title: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_set метод"
linktitle: "idx_set"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::AppearanceDictionary::idx_set метод. Представляет удобную форму для получения потоков отображения в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.pdf.annotations/appearancedictionary/idx_set/
---
## AppearanceDictionary::idx_set method


Представляет удобную форму для получения потоков внешнего вида.

```cpp
void Aspose::Pdf::Annotations::AppearanceDictionary::idx_set(const System::String &key, System::SharedPtr<XForm> value) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| key | const System::String\& | Представляет путь к потоку отображения. Если словарь отображения имеет подсловарии, то путь должен содержать 2 части ([Keys](../)), иначе путь состоит только из одной части. |

### ReturnValue

[XForm](../../../aspose.pdf/xform/) object (appearance stream) which corresponds to the given key.

## См. также

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
