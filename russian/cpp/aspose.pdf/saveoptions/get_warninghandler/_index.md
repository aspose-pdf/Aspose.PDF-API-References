---
title: "Aspose::Pdf::SaveOptions::get_WarningHandler метод"
linktitle: "get_WarningHandler"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::SaveOptions::get_WarningHandler метод. Обратный вызов для обработки любых возникших предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция сохранения продолжается, однако пользователь также может вернуть Abort, в этом случае операция сохранения должна прекратиться в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf/saveoptions/get_warninghandler/
---
## SaveOptions::get_WarningHandler method


Обратный вызов для обработки любых возникших предупреждений. WarningHandler возвращает элемент перечисления [ReturnAction](../../returnaction/), указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция сохранения продолжается, однако пользователь также может вернуть Abort, в этом случае операция сохранения должна прекратиться.

```cpp
System::SharedPtr<IWarningCallback> Aspose::Pdf::SaveOptions::get_WarningHandler() const
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [SaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
