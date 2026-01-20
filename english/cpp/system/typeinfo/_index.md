---
title: System::TypeInfo class
linktitle: TypeInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::TypeInfo class. Represents a particular type and provides information about it in C++.'
type: docs
weight: 6600
url: /cpp/system/typeinfo/
---
## TypeInfo class


Represents a particular type and provides information about it.

```cpp
class TypeInfo
```

## Nested classes

## Methods

| Method | Description |
| --- | --- |
| [AddAttribute](./addattribute/)(const ObjectPtr\&) | Adds the specified attribute to the list of type's attributes. |
| [AddDefaultConstructor](./adddefaultconstructor/)() | Sets default constructor for the type T. |
| [AddDefaultConstructor](./adddefaultconstructor/)(DefaultConstructor) | Sets default constructor by the functor that creates class instanse. |
| [AddMember](./addmember/)(const SharedPtr\<System::Reflection::MemberInfo\>\&) | Adds the specified member to the list of type's members. |
| static [BoxedValueType](./boxedvaluetype/)() | Provides unique [TypeInfo](./) structure for [BoxedValue](./boxedvalue/) type to be shared by multiple Boxed* classes. |
| [Equals](./equals/)(const TypeInfo\&) const |  |
| [get_Assembly](./get_assembly/)() const | NOT IMPLEMENTED. Returns a pointer to the assembly in which the type represented by the current object is declared. |
| [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NOT IMPLEMENTED. Returns the fully qualified name including the assembly name of the type represented by the current object. |
| [get_BaseType](./get_basetype/)() const | Returns base type descritor. |
| [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Gets a value indicating whether the current Type object has type parameters that have not been replaced by specific types. |
| [get_DeclaredMember](./get_declaredmember/)(const String\&) const | Gets list of the members with specified name. |
| [get_FullName](./get_fullname/)() const | Returns the fully qualified name (but without the assembly name) of the type represented by the current object. |
| [get_GenericTypeArguments](./get_generictypearguments/)() const | Gets an array of the generic type arguments for this type. |
| [get_IsAbstract](./get_isabstract/)() const | Gets a value indicating whether the Type is abstract and must be overridden. |
| [get_IsArray](./get_isarray/)() const | Gets a value that indicates whether the type is an array. |
| [get_IsClass](./get_isclass/)() const | Gets a value indicating whether the Type is a class or a delegate; that is, not a value type or interface. |
| [get_IsEnum](./get_isenum/)() const | Gets a value indicating whether the current Type represents an enumeration. |
| [get_IsGenericType](./get_isgenerictype/)() const |  |
| [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Gets a value indicating whether the current Type represents a generic type definition, from which other generic types can be constructed. |
| [get_IsInterface](./get_isinterface/)() const | Gets a value indicating whether the Type is an interface; that is, not a class or a value type. |
| [get_IsSealed](./get_issealed/)() const | Gets a value indicating whether the Type is declared sealed. |
| [get_IsValueType](./get_isvaluetype/)() const | Gets a value indicating whether the Type is a value type. |
| [get_IsVisible](./get_isvisible/)() const | Gets a value indicating whether the Type can be accessed by code outside the assembly. |
| [get_Name](./get_name/)() const | Returns the name of the type represented by the current object. |
| [get_Namespace](./get_namespace/)() const | Gets the namespace of the Type. |
| [GetConstructor](./getconstructor/)(const ArrayPtr\<TypeInfo\>\&) const | Searches for a public instance constructor whose parameters match the types in the specified array. |
| [GetConstructors](./getconstructors/)(System::Reflection::BindingFlags) const | searches for the constructors defined for the current Type, using the specified BindingFlags. |
| [GetConstructors](./getconstructors/)() const | Returns all the public constructors defined for the current Type. |
| [GetCustomAttribute](./getcustomattribute/)(const TypeInfo\&) const | Searches for the custom attribute applied having the specified type and applied to the type reprsented by the current object. |
| [GetCustomAttributes](./getcustomattributes/)() const | Returns an array containing objects that represent all custom attributes applied to the type. |
| [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&, bool) const | Returns an array containing objects that represent specific attributes applied to the type. |
| [GetElementType](./getelementtype/)() const | NOT IMPLEMENTED. |
| [GetField](./getfield/)(const System::String\&, System::Reflection::BindingFlags) const | Searches for the specified field, using the specified binding constraints. |
| [GetFields](./getfields/)(System::Reflection::BindingFlags) const | Searches for the fields defined for the current Type, using the specified binding constraints. |
| [GetGenericArguments](./getgenericarguments/)() const | Gets an array of the generic type arguments for this type. |
| [GetHashCode](./gethashcode/)() const | Returns a hash code associated with this instance. |
| [GetInterfaces](./getinterfaces/)() const | Gets all the interfaces implemented or inherited by the current Type. |
| [GetMember](./getmember/)(const String\&) const | Gets list of the members with specified name. |
| [GetMethod](./getmethod/)(const String\&) const | Gets method with specified name. |
| [GetProperties](./getproperties/)() const | Returns all the public properties of the current Type. |
| [GetProperties](./getproperties/)(System::Reflection::BindingFlags) const | Searches for the properties of the current Type, using the specified binding constraints. |
| [GetTemplParamType](./gettemplparamtype/)() const | Gets template parameter type descritor. |
| [Hash](./hash/)() const | Returns a hash value associated with the type represented by the current object. |
| [IsAssignableFrom](./isassignablefrom/)(const TypeInfo\&) const | Determines whether an instance of a specified type can be assigned to a variable of the current type. |
| [IsDefined](./isdefined/)(const TypeInfo\&, bool) const | NOT IMPLEMENTED. Indicates whether one or more attributes of the specified type or of its derived types is applied to this member. |
| [IsInstanceOfType](./isinstanceoftype/)(const SharedPtr\<Object\>\&) const | Determines whether the specified object is an instance of the current type. |
| [IsSubclassOf](./issubclassof/)(const TypeInfo\&) const | Determines whether the type represented by the current object is a subclass of the specified class. |
| [operator!=](./operator!=/)(const TypeInfo\&) const | Determines if the current and the specified [TypeInfo](./) objects are not equal. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Determines if the current [TypeInfo](./) object is not a null-object, i.e. it represents some type. |
| [operator==](./operator==/)(const TypeInfo\&) const | Determines if the current and the specified [TypeInfo](./) objects are equal. |
| [operator==](./operator==/)(std::nullptr_t) const | Determines if the current [TypeInfo](./) object is a null-object, i.e. does not represent any type. |
| [reset](./reset/)() | Sets [TypeInfo](./) to null. |
| [set_IsValueType](./set_isvaluetype/)(bool) | Sets a value indicating whether the Type is a value type. |
| [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Sets base type descritor. |
| [SetTemplParamType](./settemplparamtype/)(const TypeInfo\&) | Sets template parameter type descritor. |
| static [StringHash](./stringhash/)(const char_t *) | Calculates hash for specified string. |
| [ToString](./tostring/)() const | Returns a string containing the name of the type represented by the current object. |
| static [Type](./type/)() | Returns a [TypeInfo](./) object that represent [TypeInfo](./) class. |
| [TypeInfo](./typeinfo/)() | Default constructor (no type is set). |
| [TypeInfo](./typeinfo/)(std::nullptr_t) | Null object constructor (no type is set). |
| [TypeInfo](./typeinfo/)(const char_t *) | Constructor. |
| [TypeInfo](./typeinfo/)(const char_t *, uint32_t) | Constructor. |
| [TypeInfo](./typeinfo/)(const std::type_info\&) | Constructor. |
## Fields

| Field | Description |
| --- | --- |
| static [EmptyType](./emptytype/) | Constant representing empty list of [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Constant representing empty list of [TypeInfo](./). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Function pointer to construct type. |
## See Also

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
