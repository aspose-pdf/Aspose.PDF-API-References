---
title: System::Security namespace
linktitle: System::Security
second_title: Aspose.PDF for C++ API Reference
description: 'How to use System::Security namespace in C++.'
type: docs
weight: 6100
url: /cpp/system.security/
---



## Classes

| Class | Description |
| --- | --- |
| [SecureString](./securestring/) | Secure string, represents text that should be kept confidential. This class DON'T ENCRYPTING the internal data. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [SecureStringMarshal](./securestringmarshal/) | Collection of methods for allocating and copying unmanaged memory blocks. |
| [SecurityElement](./securityelement/) | XML object model for encoding security object. Not implemented. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) pointer type. |
