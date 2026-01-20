---
title: System::Reflection::ConstructorInfo class
linktitle: ConstructorInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Reflection::ConstructorInfo class. Provides access to constructor metadata in C++.'
type: docs
weight: 500
url: /cpp/system.reflection/constructorinfo/
---
## ConstructorInfo class


Provides access to constructor metadata.

```cpp
class ConstructorInfo : public System::Reflection::MethodBase
```

## Methods

| Method | Description |
| --- | --- |
| [ConstructorInfo](./constructorinfo/)(const String\&, std::function\<System::Object::ptr()>) | Initializes a new instance of the [ConstructorInfo](./) class for constructor without parameters. |
| [get_DeclaringType](./get_declaringtype/)() | Gets the class that declares this member. NOT IMPLEMENTED. |
| [get_MemberType](./get_membertype/)() const override | Gets a [MemberTypes](../membertypes/) value indicating that this member is a constructor. |
| [Invoke](./invoke/)(const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) | Invokes the method or constructor represented by the current instance, using the specified parameters. |
## See Also

* Class [MethodBase](../methodbase/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
