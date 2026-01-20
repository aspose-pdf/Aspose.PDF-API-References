---
title: System::Version class
linktitle: Version
second_title: Aspose.PDF for C++ API Reference
description: 'System::Version class. Represents a version number. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type in C++.'
type: docs
weight: 7300
url: /cpp/system/version/
---
## Version class


Represents a version number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Version
```

## Methods

| Method | Description |
| --- | --- |
| [CompareTo](./compareto/)(const Version\&) const | Compares the versions represented by the current object and the specified object. |
| [Equals](./equals/)(const Version\&) const | Determines if the version numbers represented by the current and the specified objects are equal. |
| [get_Build](./get_build/)() const | Returns the build number. |
| [get_Major](./get_major/)() const | Returns the major version. |
| [get_MajorRevision](./get_majorrevision/)() const | Returns the high 16-bit value of the revision number. |
| [get_Minor](./get_minor/)() const | Returns the minor version. |
| [get_MinorRevision](./get_minorrevision/)() const | Returns the low 16-bit value of the revision number. |
| [get_Revision](./get_revision/)() const | Returns the revision number. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code for the current object. |
| static [Parse](./parse/)(const String\&) | Converts the string representation of a version number into equivalent instance of [Version](./) class. |
| [ToString](./tostring/)() const | Returns the string representation of the version number represented by the current object. |
| [ToString](./tostring/)(int) const | Returns the string representation of the specified number of sections of version number represented by the current object. |
| [Version](./version/)(int, int, int, int) | Constructs an instance that represent the specified major, minor, build and revsion values. |
| [Version](./version/)(int, int, int) | Constructs an instance that represent the specified major, minor and build values. |
| [Version](./version/)(int, int) | Constructs an instance that represent the specified major and values. |
| [Version](./version/)(const String\&) | Constructs an instance that represent the version number represented as a string. |
| [Version](./version/)() | Constructs an instance that represents version number 0.0.-1.-1. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
