---
title: System::Security::SecureString class
linktitle: SecureString
second_title: Aspose.PDF for C++ API Reference
description: 'System::Security::SecureString class. Secure string, represents text that should be kept confidential. This class DON''T ENCRYPTING the internal data. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.security/securestring/
---
## SecureString class


Secure string, represents text that should be kept confidential. This class DON'T ENCRYPTING the internal data. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SecureString : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [AppendChar](./appendchar/)(char16_t) | Appends a character to the end of the string. |
| [Clear](./clear/)() | Delete all characters from the current secure string. |
| [Copy](./copy/)() const | Creates a duplicate of this secure string. |
| [Dispose](./dispose/)() override | Release all resources used by the current object. |
| [get_Length](./get_length/)() const | Gets number of characters in this secure string. |
| [InsertAt](./insertat/)(int32_t, char16_t) | Inserts a character at the specified index. |
| [IsReadOnly](./isreadonly/)() const | Gets flag that indicates whether this object is marked read-only. |
| [MakeReadOnly](./makereadonly/)() | Makes this secure string read-only. |
| [operator=](./operator=/)(const SecureString\&) |  |
| [RemoveAt](./removeat/)(int32_t) | Removes the character at the specified position. |
| [SecureString](./securestring/)() | RTTI information. |
| [SecureString](./securestring/)(const char16_t *, int32_t) | Constructor. |
| [SecureString](./securestring/)(const SecureString\&) |  |
| [SetAt](./setat/)(int32_t, char16_t) | Replaces the existing character at the specified position. |
| [ToUnsecureString](./tounsecurestring/)() const | Copies contents of this secure string into unsecure [String](../../system/string/) object. Use with caution. |
| [~SecureString](./~securestring/)() | Destructor. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Security](../)
* Library [Aspose.PDF for C++](../../)
