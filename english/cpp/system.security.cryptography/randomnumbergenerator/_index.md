---
title: System::Security::Cryptography::RandomNumberGenerator class
linktitle: RandomNumberGenerator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::RandomNumberGenerator class. Abstract class for random number generators to inherit from. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2600
url: /cpp/system.security.cryptography/randomnumbergenerator/
---
## RandomNumberGenerator class


Abstract class for random number generators to inherit from. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RandomNumberGenerator : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [Create](./create/)() | Creates an instance of the default implementation of a cryptographic random number generator that can be used to generate random data. Not implemented. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>) | Fills existing array elements with random bytes. |
| virtual [GetBytes](./getbytes/)(ArrayPtr\<uint8_t\>, int, int) | Fills existing array slice with random bytes. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>) | Fills existing array view elements with random bytes. |
| virtual [GetBytes](./getbytes/)(System::Details::ArrayView\<uint8_t\>, int, int) | Fills existing array view slice with random bytes. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<uint8_t, N\>\&) | Fills existing stack array elements with random bytes. |
| [GetBytes](./getbytes/)(System::Details::StackArray\<uint8_t, N\>\&, int, int) | Fills existing stack array slice with random bytes. |
| virtual [GetNonZeroBytes](./getnonzerobytes/)(ArrayPtr\<uint8_t\>) | Fills existing array elements with random non-zero bytes. |
| virtual [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<uint8_t\>) | Fills existing array view elements with random non-zero bytes. |
| [GetNonZeroBytes](./getnonzerobytes/)(System::Details::StackArray\<uint8_t, N\>\&) | Fills existing stack array elements with random non-zero bytes. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
