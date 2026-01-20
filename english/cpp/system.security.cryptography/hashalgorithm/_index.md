---
title: System::Security::Cryptography::HashAlgorithm class
linktitle: HashAlgorithm
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::HashAlgorithm class. Base class for hashing algorithms. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1600
url: /cpp/system.security.cryptography/hashalgorithm/
---
## HashAlgorithm class


Base class for hashing algorithms. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HashAlgorithm : public System::Security::Cryptography::ICryptoTransform
```

## Methods

| Method | Description |
| --- | --- |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&) | Hashes buffer. |
| [ComputeHash](./computehash/)(const ArrayPtr\<uint8_t\>\&, int, int) | Hashes buffer slice. |
| [ComputeHash](./computehash/)(SharedPtr\<IO::Stream\> const\&) | Reads stream until end and calculates hash for the data read. |
| static [Create](./create/)(const String\&) | Creates hash algorithm based on name. |
| virtual [get_Hash](./get_hash/)() | Gets value of calculated hash code. |
| virtual [get_HashSize](./get_hashsize/)() | Gets size of calculated hash value in bytes. |
| [get_InputBlockSize](./get_inputblocksize/)() override | Input block size. |
| [get_OutputBlockSize](./get_outputblocksize/)() override | Output block size. |
| virtual [Initialize](./initialize/)() | Resets hasher into initial state. |
| [TransformBlock](./transformblock/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) override | Processes block of data and copies data to output array. |
| [TransformFinalBlock](./transformfinalblock/)(ArrayPtr\<uint8_t\>, int, int) override | Processes last block of data and calculates hash. |
| virtual [~HashAlgorithm](./~hashalgorithm/)() | Destructor. |
## See Also

* Class [ICryptoTransform](../icryptotransform/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
