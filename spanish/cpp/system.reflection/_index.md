---
title: "Espacio de nombres System::Reflection"
linktitle: "System::Reflection"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Cómo usar el espacio de nombres System::Reflection en C++."
type: docs
weight: 5600
url: /es/cpp/system.reflection/
---



## Clases

| Clase | Descripción |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) clase que describe un ensamblado. El soporte es limitado ya que las reglas son bastante diferentes entre C# y C++. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [AssemblyName](./assemblyname/) | Define el nombre del ensamblado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton para registrar el tipo en el ensamblado en ejecución. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Tipo base para singletons que registran el tipo en el ensamblado en ejecución. |
| [ConstructorInfo](./constructorinfo/) | Proporciona acceso a los metadatos del constructor. |
| [FieldInfo](./fieldinfo/) | Descubre los atributos de un campo y proporciona acceso a los metadatos del campo. |
| [MemberInfo](./memberinfo/) | Proporciona información de reflexión sobre los miembros. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [MethodBase](./methodbase/) | Información base sobre el método. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [MethodInfo](./methodinfo/) | Representa información sobre el método de clase. |
| [PropertyInfo](./propertyinfo/) | Representa información de la propiedad. |
## Enums

| Enumeración | Descripción |
| --- | --- |
| [BindingFlags](./bindingflags/) | Define miembros y modos de búsqueda de tipos y enlaces. |
| [FieldAttributes](./fieldattributes/) | Atributos de campo reflejados. |
| [MemberTypes](./membertypes/) | Marca cada tipo de miembro. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | [ReflectionTypeLoadException](./reflectiontypeloadexception/) se lanza por el método Module.GetTypes si alguna de las clases en un módulo no se puede cargar. Nunca envuelva las instancias de la clase [ReflectionTypeLoadException](./reflectiontypeloadexception/) en [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | [TargetInvocationException](./targetinvocationexception/) se lanza por los métodos invocados mediante reflexión. Nunca envuelva las instancias de la clase [TargetInvocationException](./targetinvocationexception/) en [System::SmartPtr](../system/smartptr/). |
