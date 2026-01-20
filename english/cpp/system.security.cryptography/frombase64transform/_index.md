---
title: System::Security::Cryptography::FromBase64Transform class
linktitle: FromBase64Transform
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::FromBase64Transform class. Converts the CryptoStream class instance from base 64. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1500
url: /cpp/system.security.cryptography/frombase64transform/
---
## FromBase64Transform class


Converts the [CryptoStream](../cryptostream/) class instance from base 64. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FromBase64Transform : public System::Security::Cryptography::ICryptoTransform
```

## Methods

| Method | Description |
| --- | --- |
| [Clear](./clear/)() | Releases all resources. |
| [Dispose](./dispose/)() | Releases operating system resources acquired by the current object. |
| [FromBase64Transform](./frombase64transform/)() | Constructor. |
| [FromBase64Transform](./frombase64transform/)(FromBase64TransformMode) | Constructor. |
| virtual [get_CanReuseTransform](./get_canreusetransform/)() | Gets a value indicating whether the current transform can be reused. |
| [get_CanTransformMultipleBlocks](./get_cantransformmultipleblocks/)() | Gets a value indicating whether multiple blocks can be transformed. |
| virtual [get_InputBlockSize](./get_inputblocksize/)() | Input block size. |
| virtual [get_OutputBlockSize](./get_outputblocksize/)() | Output block size. |
| [TransformBlock](./transformblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) |  |
| [TransformFinalBlock](./transformfinalblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) |  |
| virtual [~FromBase64Transform](./~frombase64transform/)() | Destructor. |
## See Also

* Class [ICryptoTransform](../icryptotransform/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
