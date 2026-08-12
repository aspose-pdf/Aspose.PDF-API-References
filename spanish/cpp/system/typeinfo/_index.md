---
title: "Clase System::TypeInfo"
linktitle: "TypeInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::TypeInfo. Representa un tipo particular y proporciona información sobre él en C++."
type: docs
weight: 6900
url: /es/cpp/system/typeinfo/
---
## TypeInfo class


Representa un tipo particular y proporciona información sobre él.

```cpp
class TypeInfo
```

## Nested classes

## Métodos

| Método | Descripción |
| --- | --- |
| [AddAttribute](./addattribute/)(const ObjectPtr\&) | Agrega el atributo especificado a la lista de atributos del tipo. |
| [AddDefaultConstructor](./adddefaultconstructor/)() | Establece el constructor predeterminado para el tipo T. |
| [AddDefaultConstructor](./adddefaultconstructor/)(DefaultConstructor) | Establece el constructor predeterminado mediante el functor que crea la instancia de la clase. |
| [AddMember](./addmember/)(const SharedPtr\<System::Reflection::MemberInfo\>\&) | Agrega el miembro especificado a la lista de miembros del tipo. |
| static [BoxedValueType](./boxedvaluetype/)() | Proporciona una estructura única de [TypeInfo](./) para el tipo [BoxedValue](./boxedvalue/) que será compartida por múltiples clases Boxed*. |
| [Equals](./equals/)(const TypeInfo\&) const |  |
| [get_Assembly](./get_assembly/)() const | NO IMPLEMENTADO. Devuelve un puntero al ensamblado en el que se declara el tipo representado por el objeto actual. |
| [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NO IMPLEMENTADO. Devuelve el nombre totalmente calificado, incluido el nombre del ensamblado, del tipo representado por el objeto actual. |
| [get_BaseType](./get_basetype/)() const | Devuelve el descriptor del tipo base. |
| [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Obtiene un valor que indica si el objeto Type actual tiene parámetros de tipo que no han sido reemplazados por tipos específicos. |
| [get_DeclaredMember](./get_declaredmember/)(const String\&) const | Obtiene la lista de los miembros con el nombre especificado. |
| [get_FullName](./get_fullname/)() const | Devuelve el nombre totalmente calificado (pero sin el nombre del ensamblado) del tipo representado por el objeto actual. |
| [get_GenericTypeArguments](./get_generictypearguments/)() const | Obtiene una matriz de los argumentos de tipo genérico para este tipo. |
| [get_IsAbstract](./get_isabstract/)() const | Obtiene un valor que indica si el Type es abstracto y debe ser sobrescrito. |
| [get_IsArray](./get_isarray/)() const | Obtiene un valor que indica si el tipo es una matriz. |
| [get_IsClass](./get_isclass/)() const | Obtiene un valor que indica si el Type es una clase o un delegado; es decir, no es un tipo de valor ni una interfaz. |
| [get_IsEnum](./get_isenum/)() const | Obtiene un valor que indica si el Type actual representa una enumeración. |
| [get_IsGenericType](./get_isgenerictype/)() const |  |
| [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Obtiene un valor que indica si el Type actual representa una definición de tipo genérico, a partir de la cual se pueden construir otros tipos genéricos. |
| [get_IsInterface](./get_isinterface/)() const | Obtiene un valor que indica si el Type es una interfaz; es decir, no es una clase ni un tipo de valor. |
| [get_IsSealed](./get_issealed/)() const | Obtiene un valor que indica si el Type está declarado como sellado. |
| [get_IsValueType](./get_isvaluetype/)() const | Obtiene un valor que indica si el Type es un tipo de valor. |
| [get_IsVisible](./get_isvisible/)() const | Obtiene un valor que indica si el Type puede ser accedido por código fuera del ensamblado. |
| [get_Name](./get_name/)() const | Devuelve el nombre del tipo representado por el objeto actual. |
| [get_Namespace](./get_namespace/)() const | Obtiene el espacio de nombres del Type. |
| [GetConstructor](./getconstructor/)(const ArrayPtr\<TypeInfo\>\&) const | Busca un constructor de instancia público cuyos parámetros coincidan con los tipos en la matriz especificada. |
| [GetConstructors](./getconstructors/)(System::Reflection::BindingFlags) const | busca los constructores definidos para el Type actual, usando los BindingFlags especificados. |
| [GetConstructors](./getconstructors/)() const | Devuelve todos los constructores públicos definidos para el Type actual. |
| [GetCustomAttribute](./getcustomattribute/)(const TypeInfo\&) const | Busca el atributo personalizado aplicado que tiene el tipo especificado y que se aplica al tipo representado por el objeto actual. |
| [GetCustomAttributes](./getcustomattributes/)() const | Devuelve una matriz que contiene objetos que representan todos los atributos personalizados aplicados al tipo. |
| [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&, bool) const | Devuelve una matriz que contiene objetos que representan atributos específicos aplicados al tipo. |
| [GetElementType](./getelementtype/)() const | NO IMPLEMENTADO. |
| [GetField](./getfield/)(const System::String\&, System::Reflection::BindingFlags) const | Busca el campo especificado, usando las restricciones de enlace especificadas. |
| [GetFields](./getfields/)(System::Reflection::BindingFlags) const | Busca los campos definidos para el Type actual, usando las restricciones de enlace especificadas. |
| [GetGenericArguments](./getgenericarguments/)() const | Obtiene una matriz de los argumentos de tipo genérico para este tipo. |
| [GetHashCode](./gethashcode/)() const | Devuelve un código hash asociado a esta instancia. |
| [GetInterfaces](./getinterfaces/)() const | Obtiene todas las interfaces implementadas o heredadas por el Tipo actual. |
| [GetMember](./getmember/)(const String\&) const | Obtiene la lista de los miembros con el nombre especificado. |
| [GetMethod](./getmethod/)(const String\&) const | Obtiene el método con el nombre especificado. |
| [GetProperties](./getproperties/)() const | Devuelve todas las propiedades públicas del Tipo actual. |
| [GetProperties](./getproperties/)(System::Reflection::BindingFlags) const | Busca las propiedades del Tipo actual, usando las restricciones de enlace especificadas. |
| [GetTemplParamType](./gettemplparamtype/)() const | Obtiene el descriptor del tipo de parámetro de plantilla. |
| [Hash](./hash/)() const | Devuelve un valor hash asociado al tipo representado por el objeto actual. |
| [IsAssignableFrom](./isassignablefrom/)(const TypeInfo\&) const | Determina si una instancia de un tipo especificado puede asignarse a una variable del tipo actual. |
| [IsDefined](./isdefined/)(const TypeInfo\&, bool) const | NO IMPLEMENTADO. Indica si uno o más atributos del tipo especificado o de sus tipos derivados se aplican a este miembro. |
| [IsInstanceOfType](./isinstanceoftype/)(const SharedPtr\<Object\>\&) const | Determina si el objeto especificado es una instancia del tipo actual. |
| [IsSubclassOf](./issubclassof/)(const TypeInfo\&) const | Determina si el tipo representado por el objeto actual es una subclase de la clase especificada. |
| [operator!=](./operator!=/)(const TypeInfo\&) const | Determina si los objetos [TypeInfo](./) actuales y los especificados no son iguales. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Determina si el objeto [TypeInfo](./) actual no es un objeto nulo, es decir, representa algún tipo. |
| [operator==](./operator==/)(const TypeInfo\&) const | Determina si los objetos [TypeInfo](./) actuales y los especificados son iguales. |
| [operator==](./operator==/)(std::nullptr_t) const | Determina si el objeto [TypeInfo](./) actual es un objeto nulo, es decir, no representa ningún tipo. |
| [reset](./reset/)() | Establece [TypeInfo](./) a nulo. |
| [set_IsValueType](./set_isvaluetype/)(bool) | Establece un valor que indica si el Tipo es un tipo de valor. |
| [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Establece el descriptor del tipo base. |
| [SetTemplParamType](./settemplparamtype/)(const TypeInfo\&) | Establece el descriptor del tipo de parámetro de plantilla. |
| static [StringHash](./stringhash/)(const char_t *) | Calcula el hash para la cadena especificada. |
| [ToString](./tostring/)() const | Devuelve una cadena que contiene el nombre del tipo representado por el objeto actual. |
| static [Type](./type/)() | Devuelve un objeto [TypeInfo](./) que representa la clase [TypeInfo](./). |
| [TypeInfo](./typeinfo/)() | Constructor predeterminado (no se establece ningún tipo). |
| [TypeInfo](./typeinfo/)(std::nullptr_t) | Constructor de objeto nulo (no se establece ningún tipo). |
| [TypeInfo](./typeinfo/)(const char_t *) | Constructor. |
| [TypeInfo](./typeinfo/)(const char_t *, uint32_t) | Constructor. |
| [TypeInfo](./typeinfo/)(const std::type_info\&) | Constructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [EmptyType](./emptytype/) | Constante que representa una lista vacía de [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Constante que representa una lista vacía de [TypeInfo](./). |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Puntero a función para construir el tipo. |
## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
