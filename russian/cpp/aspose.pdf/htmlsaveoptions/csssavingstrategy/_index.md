---
title: "typedef Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy"
linktitle: "CssSavingStrategy"
second_title: "Справочник API Aspose.PDF для C++"
description: "typedef Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy. Вы можете назначить этому свойству пользовательскую стратегию, реализующую обработку и/или сохранение части CSS, созданной при конвертации PDF в HTML. В таком случае обработка (например, сохранение в поток или на диск) должна выполняться в этом пользовательском коде в C++."
type: docs
weight: 4700
url: /ru/cpp/aspose.pdf/htmlsaveoptions/csssavingstrategy/
---
## CssSavingStrategy typedef


Вы можете назначить этому свойству пользовательскую стратегию, реализующую обработку и/или сохранение части CSS, созданной при конвертации PDF в HTML. В этом случае обработка (например, сохранение в поток или на диск) должна выполняться в этом пользовательском коде.

```cpp
using Aspose::Pdf::HtmlSaveOptions::CssSavingStrategy =  System::MulticastDelegate<void(const System::SharedPtr<Aspose::Pdf::HtmlSaveOptions::CssSavingInfo>&)>
```


## См. также

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
