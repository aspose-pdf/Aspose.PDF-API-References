---
title: System::ObjectExt class
linktitle: ObjectExt
second_title: Aspose.PDF for C++ API Reference
description: 'System::ObjectExt class. Provides static methods that emulate C# Object methods called for non-Object C++ types (strings, numbers, etc.). This is a static type with no instance services. You should never create instances of it by any means in C++.'
type: docs
weight: 4900
url: /cpp/system/objectext/
---
## ObjectExt class


Provides static methods that emulate C# [Object](../object/) methods called for non-Object C++ types (strings, numbers, etc.). This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class ObjectExt : public System::ObjectType
```

## Methods

| Method | Description |
| --- | --- |
| static [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Converts array fundamental values (which C# does implicitly but C++ apparently does not). |
| static [Box](./box/)(const T\&) | Boxes value types for converting to [Object](../object/). Implementation for enum types. |
| static [Box](./box/)(const T\&) | Boxes value types for converting to [Object](../object/). Implementation for non-enum types. |
| static [Box](./box/)(const T\&) | Boxes [Nullable](../nullable/) types for converting to [Object](../object/). |
| static [Box](./box/)(const String\&) | Boxes string values. |
| static [BoxEnum](./boxenum/)(T) | Boxes enum types for being propagated as [Object](../object/). |
| static [CastToIList](./casttoilist/)(const SmartPtr\<Object\>\&) |  |
| static [Coalesce](./coalesce/)(T0, T1) | Implementation of '??' operator translation for non-nullable types. |
| static [Coalesce](./coalesce/)(System::Nullable\<T0\>, T1) | Implementation of '??' operator translation for nullable types. |
| static [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implementation of '??=' operator translation. |
| static [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementation of '??' operator translation for non-nullable types. Overload for case if RT2 is convertable to RT1. |
| static [Equals](./equals/)(const T\&, const T2\&) |  |
| static [Equals](./equals/)(const T\&, const T2\&) | Substitution for C# [Object.Equals](../object/equals/) calls working for any type in C++. Overload for smart pointer types. |
| static [Equals](./equals/)(T, const T2\&) | Substitution for C# [Object.Equals](../object/equals/) calls working for any type in C++. Overload for structure types. |
| static [Equals](./equals/)(const T\&, const T2\&) | Substitution for C# [Object.Equals](../object/equals/) calls working for any type in C++. Overload for scalar types. |
| static [Equals](./equals/)(const char_t(&), String) | Substitution for C# [Object.Equals](../object/equals/) calls working for any type in C++. Overload for string literal with string comparison. |
| static [Equals](./equals/)(const float\&, const float\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static [Equals](./equals/)(const double\&, const double\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static [GetHashCode](./gethashcode/)(const T\&) | Implements [GetHashCode()](./gethashcode/) calls; works on both [Object](../object/) subclasses and unrelated types. |
| static [Is](./is/)(const T\&) | Implements 'is' operator translation. Specialization for boxable (value) types which exactly is that they are. |
| static [Is](./is/)(const U\&) | Implements 'is' operator translation. Specialization for pointer types optimized for 'final' classes. |
| static [Is](./is/)(const U\&) | Implements 'is' operator translation. Specialization for pointer types. |
| static [Is](./is/)(const Object\&) | Implements 'is' operator translation. Specialization for value types. |
| static [Is](./is/)(const Object\&) | Implements 'is' operator translation. Specialization for unconvertible types. |
| static [Is](./is/)(const SmartPtr\<U\>\&) | Implements 'is' operator translation. Specialization for pointer types. |
| static [Is](./is/)(const ExceptionWrapper\<U\>\&) | Implements 'is' operator translation. Specialization for exception wrapper types. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Implements 'is' operator translation. Specialization for nullable types. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Implements 'is' operator translation. Specialization for boxable types with == operator defined. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Implements 'is' operator translation. Specialization for boxable types without defined ==. |
| static [Is](./is/)(const SmartPtr\<V\>\&) | Implements 'is' operator translation. Specialization value types boxed to interfaces. |
| static [Is](./is/)(const SmartPtr\<U\>\&) | Implements 'is' operator translation. Specialization for enum types. |
| static [Is](./is/)(const WeakPtr\<U\>\&) | Implements 'is' operator translation. Specialization for enum types vs weak pointers. |
| static [Is](./is/)(const Nullable\<U\>\&) | Implements 'is' operator translation. Specialization for [Nullable](../nullable/) type. |
| static [Is](./is/)(const char16_t *) | Implements 'is' operator translation. Specialization for string literal. |
| static [Is](./is/)(int32_t) | Implements 'is' operator translation. Specialization for integer literal. |
| static [IsBoxedValue](./isboxedvalue/)(const SmartPtr\<Object\>\&) | Checks if object is a boxed value. |
| static [ObjectToUnknown](./objecttounknown/)(SmartPtr\<Object\>) | Converts [Object](../object/) to unknown type, handling both smart pointer type and bpxed value situations. |
| static [ObjectToUnknown](./objecttounknown/)(SmartPtr\<Object\>) | Converts [Object](../object/) to unknown type, handling both smart pointer type and boxed value situations. |
| static [ToString](./tostring/)(const char_t *) | Substitution for C# ToString method to work on any C++ type. |
| static [ToString](./tostring/)(const Nullable\<T\>\&) | Substitution for C# ToString method to work on any C++ type. |
| static [ToString](./tostring/)(const T\&) | Substitution for C# ToString method to work on any C++ type. |
| static [ToString](./tostring/)(const T\&) | Substitution for C# ToString method to work on any C++ type. |
| static [ToString](./tostring/)(T\&) | Substitution for C# ToString method to work on any C++ type. |
| static [ToString](./tostring/)(T\&) | Substitution for C# ToString method to work on any C++ type. |
| static [ToString](./tostring/)(T\&&) | Substitution for C# ToString method to work on any C++ type. |
| static [ToString](./tostring/)(T\&) | Substitution for C# ToString method to work on any C++ type. |
| static [ToString](./tostring/)(const T\&) | Substitution for C# ToString method to work on any C++ type. |
| static [ToString](./tostring/)(T\&&) | Substitution for C# ToString method to work on any C++ type. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Unboxes value types after converting to [Object](../object/). Implementation for enum types. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Unboxes value types after converting to [Object](../object/). Implementation for non-enum & non-nullable types. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Unboxes value types after converting to [Object](../object/). Implementation for non-enum & non-nullable types. |
| static [Unbox](./unbox/)(E) | Unboxes enum types to integer. |
| static [Unbox](./unbox/)(E) | Converts enum types. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Unboxes string values. |
| static [UnboxStringSafe](./unboxstringsafe/)(const SmartPtr\<Object\>\&) | Unboxes string from boxed value. |
| static [UnboxToNullable](./unboxtonullable/)(const SmartPtr\<Object\>\&, bool) | Unboxes object to nullable type. |
| static [UnknownIsNull](./unknownisnull/)(T) | Checks whether unknown type object is nullptr. Overload for non-scalar types. |
| static [UnknownIsNull](./unknownisnull/)(T) | Checks whether unknown type object is nullptr. Overload for scalar types. |
| static [UnknownToObject](./unknowntoobject/)(T) | Converts unknown type to [Object](../object/), handling both smart pointer type and value type situations. |
| static [UnknownToObject](./unknowntoobject/)(const T\&) | Converts unknown type to [Object](../object/), handling both smart pointer type and value type situations. |
## See Also

* Class [ObjectType](../objecttype/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
