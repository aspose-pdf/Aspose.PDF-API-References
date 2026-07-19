---
title: "Класс System::Diagnostics::StackFrame"
linktitle: "StackFrame"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс System::Diagnostics::StackFrame. Получает информацию об отдельном кадре стека. Только MSVS. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 500
url: /ru/cpp/system.diagnostics/stackframe/
---
## StackFrame class


Получает информацию об отдельном кадре стека. Только MSVS. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class StackFrame : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [GetFileColumnNumber](./getfilecolumnnumber/)() | Получает номер столбца. |
| virtual [GetFileLineNumber](./getfilelinenumber/)() | Получает номер строки. |
| virtual [GetFileName](./getfilename/)() | Получает имя файла. |
| [GetMethod](./getmethod/)() | Получает информацию о методе. |
| [operator=](./operator=/)(const StackFrame\&) const | Без изменений. |
| [StackFrame](./stackframe/)(int) | Создаёт кадр стека с текущим смещением стека. |
| [StackFrame](./stackframe/)(const StackFrame\&) | Копирование не допускается. |
| virtual [~StackFrame](./~stackframe/)() | Деструктор. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
