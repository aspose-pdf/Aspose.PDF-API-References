---
title: System::Security::Cryptography::ICspAsymmetricAlgorithm class
linktitle: ICspAsymmetricAlgorithm
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::Cryptography::ICspAsymmetricAlgorithm class. Asymmetric algorithm base class. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2100
url: /cpp/system.security.cryptography/icspasymmetricalgorithm/
---
## ICspAsymmetricAlgorithm class


Asymmetric algorithm base class. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ICspAsymmetricAlgorithm : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [ExportCspBlob](./exportcspblob/)(bool) | Exports blob with key information. |
| virtual [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() | RTTI information. |
| virtual [ImportCspBlob](./importcspblob/)(ByteArrayPtr) | Imports key information from data blob. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
