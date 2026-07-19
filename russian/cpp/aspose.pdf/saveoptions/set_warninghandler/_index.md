---
title: "Aspose::Pdf::SaveOptions::set_WarningHandler метод"
linktitle: "set_WarningHandler"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::SaveOptions::set_WarningHandler метод. Обратный вызов для обработки любых возникших предупреждений. WarningHandler возвращает элемент перечисления ReturnAction, указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция сохранения продолжается, однако пользователь также может вернуть Abort, в этом случае операция сохранения должна прекратиться в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf/saveoptions/set_warninghandler/
---
## SaveOptions::set_WarningHandler method


Обратный вызов для обработки любых возникших предупреждений. WarningHandler возвращает элемент перечисления [ReturnAction](../../returnaction/), указывающий либо Continue, либо Abort. Continue является действием по умолчанию, и операция сохранения продолжается, однако пользователь также может вернуть Abort, в этом случае операция сохранения должна прекратиться.

```cpp
void Aspose::Pdf::SaveOptions::set_WarningHandler(const System::SharedPtr<IWarningCallback> &value)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [SaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
