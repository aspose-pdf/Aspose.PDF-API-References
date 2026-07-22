---
title: "System::TypeInfo klass"
linktitle: "TypeInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TypeInfo klass. Representerar en specifik typ och tillhandahåller information om den i C++."
type: docs
weight: 6900
url: /sv/cpp/system/typeinfo/
---
## TypeInfo class


Representerar en specifik typ och tillhandahåller information om den.

```cpp
class TypeInfo
```

## Nested classes

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddAttribute](./addattribute/)(const ObjectPtr\&) | Lägger till det angivna attributet i listan över typens attribut. |
| [AddDefaultConstructor](./adddefaultconstructor/)() | Ställer in standardkonstruktorn för typen T. |
| [AddDefaultConstructor](./adddefaultconstructor/)(DefaultConstructor) | Ställer in standardkonstruktorn via funktorn som skapar klassinstansen. |
| [AddMember](./addmember/)(const SharedPtr\<System::Reflection::MemberInfo\>\&) | Lägger till den angivna medlemmen i listan över typens medlemmar. |
| static [BoxedValueType](./boxedvaluetype/)() | Tillhandahåller en unik [TypeInfo](./) struktur för [BoxedValue](./boxedvalue/)-typen som kan delas av flera Boxed*-klasser. |
| [Equals](./equals/)(const TypeInfo\&) const |  |
| [get_Assembly](./get_assembly/)() const | INTE IMPLEMENTERAT. Returnerar en pekare till den assembly där typen som representeras av det aktuella objektet är deklarerad. |
| [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | INTE IMPLEMENTERAT. Returnerar det fullständigt kvalificerade namnet inklusive assembly‑namnet för typen som representeras av det aktuella objektet. |
| [get_BaseType](./get_basetype/)() const | Returnerar bastypens beskrivare. |
| [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Hämtar ett värde som indikerar om det aktuella Type‑objektet har typparametrar som inte har ersatts av specifika typer. |
| [get_DeclaredMember](./get_declaredmember/)(const String\&) const | Hämtar en lista över medlemmarna med angivet namn. |
| [get_FullName](./get_fullname/)() const | Returnerar det fullständigt kvalificerade namnet (men utan assembly‑namnet) för typen som representeras av det aktuella objektet. |
| [get_GenericTypeArguments](./get_generictypearguments/)() const | Hämtar en array av de generiska typargumenten för denna typ. |
| [get_IsAbstract](./get_isabstract/)() const | Hämtar ett värde som indikerar om Type är abstrakt och måste åsidosättas. |
| [get_IsArray](./get_isarray/)() const | Hämtar ett värde som indikerar om typen är en array. |
| [get_IsClass](./get_isclass/)() const | Hämtar ett värde som indikerar om Type är en klass eller en delegat; det vill säga, inte en värdetyp eller ett gränssnitt. |
| [get_IsEnum](./get_isenum/)() const | Hämtar ett värde som indikerar om den aktuella Type representerar en uppräkning. |
| [get_IsGenericType](./get_isgenerictype/)() const |  |
| [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Hämtar ett värde som indikerar om den aktuella Type representerar en generisk typdefinition, från vilken andra generiska typer kan konstrueras. |
| [get_IsInterface](./get_isinterface/)() const | Hämtar ett värde som indikerar om typen är ett gränssnitt; det vill säga, inte en klass eller en värdetyp. |
| [get_IsSealed](./get_issealed/)() const | Hämtar ett värde som indikerar om typen är deklarerad som sealed. |
| [get_IsValueType](./get_isvaluetype/)() const | Hämtar ett värde som indikerar om typen är en värdetyp. |
| [get_IsVisible](./get_isvisible/)() const | Hämtar ett värde som indikerar om typen kan nås av kod utanför samlingen. |
| [get_Name](./get_name/)() const | Returnerar namnet på typen som representeras av det aktuella objektet. |
| [get_Namespace](./get_namespace/)() const | Hämtar namnutrymmet för typen. |
| [GetConstructor](./getconstructor/)(const ArrayPtr\<TypeInfo\>\&) const | Söker efter en offentlig instanskonstruktor vars parametrar matchar typerna i den angivna arrayen. |
| [GetConstructors](./getconstructors/)(System::Reflection::BindingFlags) const | söker efter konstruktorerna som definierats för den aktuella typen, med hjälp av de angivna BindingFlags. |
| [GetConstructors](./getconstructors/)() const | Returnerar alla offentliga konstruktorer som definierats för den aktuella typen. |
| [GetCustomAttribute](./getcustomattribute/)(const TypeInfo\&) const | Söker efter det anpassade attributet som har den angivna typen och som är tillämpat på typen som representeras av det aktuella objektet. |
| [GetCustomAttributes](./getcustomattributes/)() const | Returnerar en array som innehåller objekt som representerar alla anpassade attribut som tillämpats på typen. |
| [GetCustomAttributes](./getcustomattributes/)(const TypeInfo\&, bool) const | Returnerar en array som innehåller objekt som representerar specifika attribut som tillämpats på typen. |
| [GetElementType](./getelementtype/)() const | INTE IMPLEMENTERAD. |
| [GetField](./getfield/)(const System::String\&, System::Reflection::BindingFlags) const | Söker efter det angivna fältet, med hjälp av de angivna bindningsrestriktionerna. |
| [GetFields](./getfields/)(System::Reflection::BindingFlags) const | Söker efter fälten som definierats för den aktuella typen, med hjälp av de angivna bindningsrestriktionerna. |
| [GetGenericArguments](./getgenericarguments/)() const | Hämtar en array av de generiska typargumenten för denna typ. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod som är associerad med den här instansen. |
| [GetInterfaces](./getinterfaces/)() const | Hämtar alla gränssnitt som implementeras eller ärvs av den aktuella typen. |
| [GetMember](./getmember/)(const String\&) const | Hämtar en lista över medlemmarna med angivet namn. |
| [GetMethod](./getmethod/)(const String\&) const | Hämtar metod med angivet namn. |
| [GetProperties](./getproperties/)() const | Returnerar alla offentliga egenskaper för den aktuella typen. |
| [GetProperties](./getproperties/)(System::Reflection::BindingFlags) const | Söker efter egenskaperna för den aktuella typen, med hjälp av de angivna bindningsrestriktionerna. |
| [GetTemplParamType](./gettemplparamtype/)() const | Hämtar mallparameter-typbeskrivare. |
| [Hash](./hash/)() const | Returnerar ett hashvärde som är associerat med typen som representeras av det aktuella objektet. |
| [IsAssignableFrom](./isassignablefrom/)(const TypeInfo\&) const | Bestämmer om en instans av en angiven typ kan tilldelas en variabel av den aktuella typen. |
| [IsDefined](./isdefined/)(const TypeInfo\&, bool) const | INTE IMPLEMENTERAD. Indikerar om ett eller flera attribut av den angivna typen eller av dess avledda typer är tillämpade på detta medlem. |
| [IsInstanceOfType](./isinstanceoftype/)(const SharedPtr\<Object\>\&) const | Bestämmer om det angivna objektet är en instans av den aktuella typen. |
| [IsSubclassOf](./issubclassof/)(const TypeInfo\&) const | Bestämmer om typen som representeras av det aktuella objektet är en underklass till den angivna klassen. |
| [operator!=](./operator!=/)(const TypeInfo\&) const | Bestämmer om de aktuella och de angivna [TypeInfo](./)-objekten inte är lika. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Bestämmer om det aktuella [TypeInfo](./)-objektet inte är ett null-objekt, d.v.s. det representerar någon typ. |
| [operator==](./operator==/)(const TypeInfo\&) const | Bestämmer om de aktuella och de angivna [TypeInfo](./)-objekten är lika. |
| [operator==](./operator==/)(std::nullptr_t) const | Bestämmer om det aktuella [TypeInfo](./)-objektet är ett null-objekt, d.v.s. det representerar ingen typ. |
| [reset](./reset/)() | Sätter [TypeInfo](./) till null. |
| [set_IsValueType](./set_isvaluetype/)(bool) | Sätter ett värde som indikerar om typen är en värdetyp. |
| [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Sätter bastypens beskrivare. |
| [SetTemplParamType](./settemplparamtype/)(const TypeInfo\&) | Sätter mallparameter-typens beskrivare. |
| static [StringHash](./stringhash/)(const char_t *) | Beräknar hash för den angivna strängen. |
| [ToString](./tostring/)() const | Returnerar en sträng som innehåller namnet på den typ som representeras av det aktuella objektet. |
| static [Type](./type/)() | Returnerar ett [TypeInfo](./)-objekt som representerar [TypeInfo](./)-klassen. |
| [TypeInfo](./typeinfo/)() | Standardkonstruktor (ingen typ är angiven). |
| [TypeInfo](./typeinfo/)(std::nullptr_t) | Null-objektkonstruktor (ingen typ är angiven). |
| [TypeInfo](./typeinfo/)(const char_t *) | Konstruktor. |
| [TypeInfo](./typeinfo/)(const char_t *, uint32_t) | Konstruktor. |
| [TypeInfo](./typeinfo/)(const std::type_info\&) | Konstruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [EmptyType](./emptytype/) | Konstant som representerar en tom lista av [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Konstant som representerar en tom lista av [TypeInfo](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Funktionspekare för att konstruera typen. |
## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
