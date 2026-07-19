---
title: "Класс Aspose::Pdf::Multithreading::InterruptMonitor"
linktitle: "InterruptMonitor"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Multithreading::InterruptMonitor. Представляет информацию о прерывании в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class


Представляет информацию об прерывании.

```cpp
class InterruptMonitor : public Aspose::Pdf::Multithreading::IInterruptMonitor
```

## Методы

| Метод | Описание |
| --- | --- |
| [Dispose](./dispose/)() override | Освобождает используемые ресурсы. |
| [get_CancellationToken](./get_cancellationtoken/)() override | Токен отмены монитора, используемый для прерывания процесса. По умолчанию каждый [IInterruptMonitor](../iinterruptmonitor/) генерирует собственный cancellationSource. |
| static [get_ThreadLocalInstance](./get_threadlocalinstance/)() | Получает экземпляр [IInterruptMonitor](../iinterruptmonitor/), уникальный для каждого потока. |
| [Interrupt](./interrupt/)() override | Отправляет запрос на прерывание операций. |
| [InterruptMonitor](./interruptmonitor/)() | Инициализирует новый экземпляр класса [InterruptMonitor](./). |
| static [set_ThreadLocalInstance](./set_threadlocalinstance/)(const System::SharedPtr\<IInterruptMonitor\>\&) | Устанавливает экземпляр [IInterruptMonitor](../iinterruptmonitor/), уникальный для каждого потока. |
## См. также

* Class [IInterruptMonitor](../iinterruptmonitor/)
* Namespace [Aspose::Pdf::Multithreading](../)
* Library [Aspose.PDF for C++](../../)
