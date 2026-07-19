---
title: "Aspose::Pdf::LoadOptions::set_WarningHandler method"
linktitle: "set_WarningHandler"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LoadOptions::set_WarningHandler method. Обратный вызов для обработки любых генерируемых предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция Load продолжается, однако пользователь может также вернуть Abort, в этом случае операция Load должна быть прекращена в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf/loadoptions/set_warninghandler/
---
## LoadOptions::set_WarningHandler method


Обратный вызов для обработки любых генерируемых предупреждений. WarningHandler возвращает элемент перечисления [ReturnAction](../../returnaction/), указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция Load продолжается, однако пользователь может также вернуть Abort, в этом случае операция Load должна быть прекращена.

```cpp
void Aspose::Pdf::LoadOptions::set_WarningHandler(const System::SharedPtr<IWarningCallback> &value)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
