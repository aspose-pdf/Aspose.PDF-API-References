---
title: "System::Security::Cryptography::ICryptoTransform класс"
linktitle: "ICryptoTransform"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::ICryptoTransform класс. Базовый класс криптографического трансформера. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 2000
url: /ru/cpp/system.security.cryptography/icryptotransform/
---
## ICryptoTransform class


Базовый класс криптографического трансформера. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/) function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ICryptoTransform : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_InputBlockSize](./get_inputblocksize/)() | Размер входного блока. |
| virtual [get_OutputBlockSize](./get_outputblocksize/)() | Размер выходного блока. |
| virtual [TransformBlock](./transformblock/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) | Информация RTTI. |
| virtual [TransformFinalBlock](./transformfinalblock/)(ArrayPtr\<uint8_t\>, int, int) | Обрабатывает последний блок данных и вычисляет выходное значение. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
