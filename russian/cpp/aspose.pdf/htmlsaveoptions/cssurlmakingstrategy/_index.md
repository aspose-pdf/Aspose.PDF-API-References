---
title: "typedef Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy"
linktitle: "CssUrlMakingStrategy"
second_title: "Справочник API Aspose.PDF для C++"
description: "typedef Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy. Вы можете назначить этому свойству делегат, созданный из пользовательского метода, который реализует создание URL CSS, на который ссылается сгенерированный HTML‑документ. Например, если вы хотите, чтобы CSS в HTML ссылался как \"otherPage.ASPX?CssID=zjjkklj\", то такая пользовательская стратегия должна возвращать \"otherPage.ASPX?CssID=zjjkklj\" в C++."
type: docs
weight: 4800
url: /ru/cpp/aspose.pdf/htmlsaveoptions/cssurlmakingstrategy/
---
## CssUrlMakingStrategy typedef


Вы можете назначить этому свойству делегат, созданный из пользовательского метода, который реализует создание URL CSS, на который ссылается сгенерированный HTML‑документ. Например, если вы хотите, чтобы CSS в HTML ссылался, например, как \"otherPage.ASPX?CssID=zjjkklj\", то такая пользовательская стратегия должна возвращать \"otherPage.ASPX?CssID=zjjkklj\".

```cpp
using Aspose::Pdf::HtmlSaveOptions::CssUrlMakingStrategy =  System::MulticastDelegate<System::String(const System::SharedPtr<Aspose::Pdf::HtmlSaveOptions::CssUrlRequestInfo>&)>
```


## См. также

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
