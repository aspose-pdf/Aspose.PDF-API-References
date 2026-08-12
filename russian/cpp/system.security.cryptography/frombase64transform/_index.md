---
title: "System::Security::Cryptography::FromBase64Transform класс"
linktitle: "FromBase64Transform"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Security::Cryptography::FromBase64Transform класс. Преобразует экземпляр класса CryptoStream из base 64. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента в C++."
type: docs
weight: 1500
url: /ru/cpp/system.security.cryptography/frombase64transform/
---
## FromBase64Transform class


Преобразует экземпляр класса [CryptoStream](../cryptostream/) из base 64. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class FromBase64Transform : public System::Security::Cryptography::ICryptoTransform
```

## Методы

| Метод | Описание |
| --- | --- |
| [Clear](./clear/)() | Освобождает все ресурсы. |
| [Dispose](./dispose/)() | Освобождает ресурсы операционной системы, захваченные текущим объектом. |
| [FromBase64Transform](./frombase64transform/)() | Конструктор. |
| [FromBase64Transform](./frombase64transform/)(FromBase64TransformMode) | Конструктор. |
| virtual [get_CanReuseTransform](./get_canreusetransform/)() | Возвращает значение, указывающее, может ли текущий трансформ быть переиспользован. |
| [get_CanTransformMultipleBlocks](./get_cantransformmultipleblocks/)() | Возвращает значение, указывающее, могут ли быть преобразованы несколько блоков. |
| virtual [get_InputBlockSize](./get_inputblocksize/)() | Размер входного блока. |
| virtual [get_OutputBlockSize](./get_outputblocksize/)() | Размер выходного блока. |
| [TransformBlock](./transformblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) |  |
| [TransformFinalBlock](./transformfinalblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) |  |
| virtual [~FromBase64Transform](./~frombase64transform/)() | Деструктор. |
## См. также

* Class [ICryptoTransform](../icryptotransform/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
