---
title: "Aspose::Pdf::LoadOptions::get_WarningHandler method"
linktitle: "get_WarningHandler"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LoadOptions::get_WarningHandler method. Обратный вызов для обработки любых генерируемых предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция Load продолжается, однако пользователь может также вернуть Abort, в этом случае операция Load должна быть прекращена в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf/loadoptions/get_warninghandler/
---
## LoadOptions::get_WarningHandler method


Обратный вызов для обработки любых генерируемых предупреждений. WarningHandler возвращает элемент перечисления [ReturnAction](../../returnaction/), указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция Load продолжается, однако пользователь может также вернуть Abort, в этом случае операция Load должна быть прекращена.

```cpp
System::SharedPtr<IWarningCallback> Aspose::Pdf::LoadOptions::get_WarningHandler() const
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
