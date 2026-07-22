---
title: "System::Reflection namnrymd"
linktitle: "System::Reflection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder System::Reflection namnrymd i C++."
type: docs
weight: 5600
url: /sv/cpp/system.reflection/
---



## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) klass som beskriver assembly. Stödet är begränsat eftersom reglerna är ganska olika mellan C# och C++. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [AssemblyName](./assemblyname/) | Definierar assembly‑namn. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton för att registrera typ i den körande assemblyn. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Bastyp för singletons för att registrera typ i den körande assemblyn. |
| [ConstructorInfo](./constructorinfo/) | Tillhandahåller åtkomst till konstruktörsmetadata. |
| [FieldInfo](./fieldinfo/) | Upptäcker attributen för ett fält och tillhandahåller åtkomst till fältmetadata. |
| [MemberInfo](./memberinfo/) | Tillhandahåller reflektioninformation om medlemmar. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [MethodBase](./methodbase/) | Grundläggande information om metod. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [MethodInfo](./methodinfo/) | Representerar information om klassmetod. |
| [PropertyInfo](./propertyinfo/) | Representerar egenskapsinformation. |
## Enums

| Enum | Beskrivning |
| --- | --- |
| [BindingFlags](./bindingflags/) | Definierar medlemmar och typer för uppslagningslägen och bindningar. |
| [FieldAttributes](./fieldattributes/) | Reflekterade fältattribut. |
| [MemberTypes](./membertypes/) | Markerar varje typ av medlem. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | [ReflectionTypeLoadException](./reflectiontypeloadexception/) kastas av metoden Module.GetTypes om någon av klasserna i en modul misslyckas med att laddas. Omslut aldrig klassinstanser av [ReflectionTypeLoadException](./reflectiontypeloadexception/) med [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | [TargetInvocationException](./targetinvocationexception/) kastas av metoder som anropas via reflektion. Omslut aldrig klassinstanser av [TargetInvocationException](./targetinvocationexception/) med [System::SmartPtr](../system/smartptr/). |
