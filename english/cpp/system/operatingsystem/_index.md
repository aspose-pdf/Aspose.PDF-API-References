---
title: System::OperatingSystem class
linktitle: OperatingSystem
second_title: Aspose.PDF for C++ API Reference
description: 'System::OperatingSystem class. Represents a particular operating system and provides information about it. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 5100
url: /cpp/system/operatingsystem/
---
## OperatingSystem class


Represents a particular operating system and provides information about it. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class OperatingSystem
```

## Methods

| Method | Description |
| --- | --- |
| [get_Platform](./get_platform/)() const | Returns the platform identifier of the operating system represented by the current object. |
| [get_ServicePack](./get_servicepack/)() const | Returns the service pack name of the operating system represented by the current object. |
| [get_Version](./get_version/)() const | Returns a constant reference to a [Version](../version/) object representing the version of the operating system represented by the current object. |
| [get_VersionString](./get_versionstring/)() const | Returns the string representation of the version of the operating system represented by the current object. |
| [OperatingSystem](./operatingsystem/)(PlatformID, const Version\&) | Constructs an instance that represents an operating system specified as particular platform id and version. |
| [OperatingSystem](./operatingsystem/)(PlatformID, const Version\&, const String\&) | Constructs an instance that represents an operating system specified as particular platform id, version and service pack. |
| [ToString](./tostring/)() const | Returns the string representation of the version of the operating system represented by the current object. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
