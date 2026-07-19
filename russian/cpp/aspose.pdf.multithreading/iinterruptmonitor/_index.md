---
title: "Класс Aspose::Pdf::Multithreading::IInterruptMonitor"
linktitle: "IInterruptMonitor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Multithreading::IInterruptMonitor. Представляет информацию о прерывании в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor class


Представляет информацию об прерывании.

```cpp
class IInterruptMonitor : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_CancellationToken](./get_cancellationtoken/)() | Токен отмены монитора, используемый для прерывания процесса. По умолчанию каждый [IInterruptMonitor](./) генерирует собственный cancellationSource. |
| virtual [Interrupt](./interrupt/)() | Отправляет запрос на прерывание операций. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf::Multithreading](../)
* Library [Aspose.PDF for C++](../../)
