---
title: System::Security::Cryptography::ICryptoTransform class
linktitle: ICryptoTransform
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ICryptoTransform class. Base class of cryptographic transformer. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2000
url: /cpp/system.security.cryptography/icryptotransform/
---
## ICryptoTransform class


Base class of cryptographic transformer. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICryptoTransform : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_InputBlockSize](./get_inputblocksize/)() | Input block size. |
| virtual [get_OutputBlockSize](./get_outputblocksize/)() | Output block size. |
| virtual [TransformBlock](./transformblock/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) | RTTI information. |
| virtual [TransformFinalBlock](./transformfinalblock/)(ArrayPtr\<uint8_t\>, int, int) | Processes last block of data and calculates output value. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
