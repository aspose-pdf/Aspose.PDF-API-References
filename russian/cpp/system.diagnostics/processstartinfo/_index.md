---
title: "System::Diagnostics::ProcessStartInfo класс"
linktitle: "ProcessStartInfo"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Diagnostics::ProcessStartInfo класс. Описывает параметры запуска процесса. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 400
url: /ru/cpp/system.diagnostics/processstartinfo/
---
## ProcessStartInfo class


Описывает параметры запуска процесса. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ProcessStartInfo : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_Arguments](./get_arguments/)() const | Получает аргументы процесса. |
| [get_CreateNoWindow](./get_createnowindow/)() const | Получает свойство NoWindow. |
| [get_EnvironmentVariables](./get_environmentvariables/)() const | Получает переменные окружения процесса. |
| [get_FileName](./get_filename/)() const | Получает имя файла процесса. |
| [get_RedirectStandardError](./get_redirectstandarderror/)() const | Получает свойство RedirectStandardError. |
| [get_RedirectStandardInput](./get_redirectstandardinput/)() const | Получает свойство RedirectStandardInput. |
| [get_RedirectStandardOutput](./get_redirectstandardoutput/)() const | Получает свойство RedirectStandardOutput. |
| [get_UseShellExecute](./get_useshellexecute/)() const | Получает свойство UseShellExecute. |
| [get_WindowStyle](./get_windowstyle/)() const | Получает стиль окна. |
| [get_WorkingDirectory](./get_workingdirectory/)() const | Получает рабочий каталог процесса. |
| [ProcessStartInfo](./processstartinfo/)() | Создаёт пустой объект информации о запуске. |
| [ProcessStartInfo](./processstartinfo/)(const String\&) | Создаёт объект информации о запуске. |
| [ProcessStartInfo](./processstartinfo/)(const String\&, const String\&) | Создаёт объект информации о запуске. |
| [set_Arguments](./set_arguments/)(const String\&) | Устанавливает аргументы процесса. |
| [set_CreateNoWindow](./set_createnowindow/)(bool) | Устанавливает свойство NoWindow. |
| [set_FileName](./set_filename/)(const String\&) | Устанавливает имя файла процесса. |
| [set_RedirectStandardError](./set_redirectstandarderror/)(bool) | Устанавливает свойство RedirectStandardError. |
| [set_RedirectStandardInput](./set_redirectstandardinput/)(bool) | Устанавливает свойство RedirectStandardInput. |
| [set_RedirectStandardOutput](./set_redirectstandardoutput/)(bool) | Устанавливает свойство RedirectStandardOutput. |
| [set_UseShellExecute](./set_useshellexecute/)(bool) | Устанавливает свойство UseShellExecute. |
| [set_WindowStyle](./set_windowstyle/)(ProcessWindowStyle) | Устанавливает стиль окна. |
| [set_WorkingDirectory](./set_workingdirectory/)(const String\&) | Устанавливает рабочий каталог процесса. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
