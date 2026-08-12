---
title: "System::Diagnostics::Process class"
linktitle: "Process"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Diagnostics::Process class. Инкапсулирует информацию о процессе и его управление. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 300
url: /ru/cpp/system.diagnostics/process/
---
## Process class


Инкапсулирует информацию о процессе и его управление. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Process : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_EnableRaisingEvents](./get_enableraisingevents/)() const | Получает, следует ли генерировать событие Exited при завершении процесса. |
| [get_ExitCode](./get_exitcode/)() const | Получает код завершения процесса. |
| [get_PrivateMemorySize64](./get_privatememorysize64/)() const | Получает размер приватного набора памяти процесса. |
| [get_ProcessName](./get_processname/)() const | Получает имя процесса. |
| [get_StandardError](./get_standarderror/)() const | Предоставляет средство чтения вывода ошибок процесса. Не реализовано. |
| [get_StandardOutput](./get_standardoutput/)() const | Предоставляет средство чтения стандартного вывода процесса. Не реализовано. |
| [get_StartInfo](./get_startinfo/)() const | Получает информацию о запуске процесса. |
| [get_WorkingSet64](./get_workingset64/)() const | Получает размер рабочего набора памяти процесса. |
| static [GetCurrentProcess](./getcurrentprocess/)() | Получает информацию о текущем процессе. Только [Windows](../../system.windows/). |
| [GetOutputText](./getoutputtext/)() const | Получает текст вывода процесса. |
| [set_EnableRaisingEvents](./set_enableraisingevents/)(bool) | Устанавливает, следует ли генерировать событие Exited при завершении процесса. |
| [Start](./start/)() | Запускает процесс с предопределёнными параметрами. |
| static [Start](./start/)(const String\&, const String\&) | Запускает процесс с указанным путём и аргументами. |
| static [Start](./start/)(const SharedPtr\<ProcessStartInfo\>\&) | Запускает процесс с указанным путём и аргументами. |
| [WaitForExit](./waitforexit/)(int) | Ожидает завершения процесса. Не реализовано. |
| [WaitForExit](./waitforexit/)() | Ожидает завершения процесса, не возвращается, пока он не завершится. |
| virtual [~Process](./~process/)() | Деструктор. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
