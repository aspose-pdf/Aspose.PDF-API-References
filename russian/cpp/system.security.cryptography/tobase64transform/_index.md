---
title: "System::Security::Cryptography::ToBase64Transform класс"
linktitle: "ToBase64Transform"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::ToBase64Transform класс. Преобразует экземпляр класса CryptoStream в base 64. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 5000
url: /ru/cpp/system.security.cryptography/tobase64transform/
---
## ToBase64Transform class


Преобразует экземпляр класса [CryptoStream](../cryptostream/) в base 64. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ToBase64Transform : public System::Security::Cryptography::ICryptoTransform
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clear](./clear/)() | Освобождает все ресурсы. |
| [Dispose](./dispose/)() | Освобождает ресурсы операционной системы, захваченные текущим объектом. |
| virtual [get_CanReuseTransform](./get_canreusetransform/)() | Возвращает значение, указывающее, может ли текущий трансформ быть переиспользован. |
| [get_CanTransformMultipleBlocks](./get_cantransformmultipleblocks/)() | Возвращает значение, указывающее, могут ли быть преобразованы несколько блоков. |
| virtual [get_InputBlockSize](./get_inputblocksize/)() | Размер входного блока. |
| virtual [get_OutputBlockSize](./get_outputblocksize/)() | Размер выходного блока. |
| [TransformBlock](./transformblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) | Обрабатывает блок данных и копирует данные в выходной массив. |
| [TransformFinalBlock](./transformfinalblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) | Обрабатывает последний блок данных и вычисляет выходное значение. |
| virtual [~ToBase64Transform](./~tobase64transform/)() | Деструктор. |
## См. также

* Class [ICryptoTransform](../icryptotransform/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
