---
title: "System::IO::StringReader класс"
linktitle: "StringReader"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::StringReader class. Представляет считыватель, который читает символы из строки. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2400
url: /ru/cpp/system.io/stringreader/
---
## StringReader class


Представляет считыватель, который читает символы из строки. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/) . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class StringReader : public System::IO::TextReader
```

## Методы

| Метод | Описание |
| --- | --- |
| [Close](./close/)() override | Закрывает поток. |
| [Dispose](./dispose/)() override | Ничего не делает. |
| [Dispose](./dispose/)(bool) override | Ничего не делает. |
| [Peek](./peek/)() override | Читает один символ из потока, не изменяя позицию потока. |
| [Read](./read/)() override | Читает один символ из потока. |
| [Read](./read/)(ArrayPtr\<char_t\>, int, int) override | Читает указанное количество символов из потока в указанный массив символов, начиная с указанной позиции. |
| [ReadLine](./readline/)() override | Читает символы из потока до конца текущей строки. |
| [ReadToEnd](./readtoend/)() override | Читает символы из потока до конца потока. |
| [StringReader](./stringreader/)(const String\&) | Создаёт новый экземпляр класса [StringReader](./), который читает символы из указанной строки. |
## См. также

* Class [TextReader](../textreader/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
