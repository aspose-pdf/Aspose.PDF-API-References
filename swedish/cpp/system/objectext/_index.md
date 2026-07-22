---
title: "System::ObjectExt klass"
linktitle: "ObjectExt"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ObjectExt klass. Tillhandahåller statiska metoder som efterliknar C# Object‑metoder som anropas för icke‑Object C++‑typer (strängar, tal, etc.). Detta är en statisk typ utan instans‑tjänster. Du bör aldrig skapa instanser av den på något sätt i C++."
type: docs
weight: 5100
url: /sv/cpp/system/objectext/
---
## ObjectExt class


Tillhandahåller statiska metoder som efterliknar C# [Object](../object/)-metoder som anropas för icke‑Object C++‑typer (strängar, tal, etc.). Detta är en statisk typ utan instans‑tjänster. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class ObjectExt : public System::ObjectType
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Konverterar grundläggande arrayvärden (vilket C# gör implicit men C++ uppenbarligen inte gör). |
| static [Box](./box/)(const T\&) | Packar värdetyper för konvertering till [Object](../object/). Implementation för enum‑typer. |
| static [Box](./box/)(const T\&) | Packar värdetyper för konvertering till [Object](../object/). Implementation för icke‑enum‑typer. |
| static [Box](./box/)(const T\&) | Packar [Nullable](../nullable/)-typer för konvertering till [Object](../object/). |
| static [Box](./box/)(const String\&) | Packar strängvärden. |
| static [BoxEnum](./boxenum/)(T) | Packar enum‑typer för att vidarebefordras som [Object](../object/). |
| static [CastToIList](./casttoilist/)(const SmartPtr\<Object\>\&) |  |
| static [Coalesce](./coalesce/)(T0, T1) | Implementering av översättning av '??'-operatorn för icke‑nullbara typer. |
| static [Coalesce](./coalesce/)(System::Nullable\<T0\>, T1) | Implementering av översättning av '??'-operatorn för nullbara typer. |
| static [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implementering av översättning av '??='-operatorn. |
| static [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementering av översättning av '??'-operatorn för icke-nullbara typer. Överlagring för fallet då RT2 kan konverteras till RT1. |
| static [Equals](./equals/)(const T\&, const T2\&) |  |
| static [Equals](./equals/)(const T\&, const T2\&) | Ersättning för C# [Object.Equals](../object/equals/)-anrop som fungerar för alla typer i C++. Överlagring för smarta pekartyper. |
| static [Equals](./equals/)(T, const T2\&) | Ersättning för C# [Object.Equals](../object/equals/)-anrop som fungerar för alla typer i C++. Överlagring för strukturtyper. |
| static [Equals](./equals/)(const T\&, const T2\&) | Ersättning för C# [Object.Equals](../object/equals/)-anrop som fungerar för alla typer i C++. Överlagring för skalära typer. |
| static [Equals](./equals/)(const char_t(&), String) | Ersättning för C# [Object.Equals](../object/equals/)-anrop som fungerar för alla typer i C++. Överlagring för strängliteral med strängjämförelse. |
| static [Equals](./equals/)(const float\&, const float\&) | Emulerar C#-stil flyttalsjämförelse där två NaN‑värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static [Equals](./equals/)(const double\&, const double\&) | Emulerar C#-stil flyttalsjämförelse där två NaN‑värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static [GetHashCode](./gethashcode/)(const T\&) | Implementerar [GetHashCode()](./gethashcode/)-anrop; fungerar för både [Object](../object/)-subklasser och orelaterade typer. |
| static [Is](./is/)(const T\&) | Implementerar översättning av 'is'-operatorn. Specialisering för boxbara (värde)typer, vilket exakt är vad de är. |
| static [Is](./is/)(const U\&) | Implementerar översättning av 'is'-operatorn. Specialisering för pekartyper optimerade för 'final'-klasser. |
| static [Is](./is/)(const U\&) | Implementerar översättning av 'is'-operatorn. Specialisering för pekartyper. |
| static [Is](./is/)(const Object\&) | Implementerar översättning av 'is'-operatorn. Specialisering för värdetyper. |
| static [Is](./is/)(const Object\&) | Implementerar översättning av 'is'-operatorn. Specialisering för icke-konverterbara typer. |
| static [Is](./is/)(const SmartPtr\<U\>\&) | Implementerar översättning av 'is'-operatorn. Specialisering för pekartyper. |
| static [Is](./is/)(const ExceptionWrapper\<U\>\&) | Implementerar översättning av 'is'-operatorn. Specialisering för undantagsomslagstyper. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Implementerar översättning av 'is'-operatorn. Specialisering för nullable-typer. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Implementerar översättning av 'is'-operatorn. Specialisering för boxbara typer med definierad ==-operator. |
| static [Is](./is/)(const SmartPtr\<Object\>\&) | Implementerar översättning av 'is'-operatorn. Specialisering för boxbara typer utan definierad ==. |
| static [Is](./is/)(const SmartPtr\<V\>\&) | Implementerar översättning av 'is'-operatorn. Specialisering för värdetyper som är boxade till gränssnitt. |
| static [Is](./is/)(const SmartPtr\<U\>\&) | Implementerar översättning av 'is'-operatorn. Specialisering för enum-typer. |
| static [Is](./is/)(const WeakPtr\<U\>\&) | Implementerar översättning av 'is'-operatorn. Specialisering för enum-typer kontra svaga pekare. |
| static [Is](./is/)(const Nullable\<U\>\&) | Implementerar översättning av 'is'-operatorn. Specialisering för [Nullable](../nullable/)-typen. |
| static [Is](./is/)(const char16_t *) | Implementerar översättning av 'is'-operatorn. Specialisering för strängliteral. |
| static [Is](./is/)(int32_t) | Implementerar översättning av 'is'-operatorn. Specialisering för heltalsliteral. |
| static [IsBoxedValue](./isboxedvalue/)(const SmartPtr\<Object\>\&) | Kontrollerar om objektet är ett boxat värde. |
| static [ObjectToUnknown](./objecttounknown/)(SmartPtr\<Object\>) | Konverterar [Object](../object/) till okänd typ, hanterar både smarta pekartyper och bpxed-värdesituationer. |
| static [ObjectToUnknown](./objecttounknown/)(SmartPtr\<Object\>) | Konverterar [Object](../object/) till okänd typ, hanterar både smarta pekartyper och boxade värdesituationer. |
| static [ToString](./tostring/)(const char_t *) | Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst. |
| static [ToString](./tostring/)(const Nullable\<T\>\&) | Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst. |
| static [ToString](./tostring/)(const T\&) | Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst. |
| static [ToString](./tostring/)(const T\&) | Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst. |
| static [ToString](./tostring/)(T\&) | Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst. |
| static [ToString](./tostring/)(T\&) | Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst. |
| static [ToString](./tostring/)(T\&&) | Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst. |
| static [ToString](./tostring/)(T\&) | Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst. |
| static [ToString](./tostring/)(const T\&) | Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst. |
| static [ToString](./tostring/)(T\&&) | Ersättning för C# ToString-metoden för att fungera på vilken C++-typ som helst. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Packar upp värdetyper efter konvertering till [Object](../object/). Implementering för enum-typer. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Packar upp värdetyper efter konvertering till [Object](../object/). Implementering för icke-enum & icke-nullbara typer. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Packar upp värdetyper efter konvertering till [Object](../object/). Implementering för icke-enum & icke-nullbara typer. |
| static [Unbox](./unbox/)(E) | Packar upp enum-typer till heltal. |
| static [Unbox](./unbox/)(E) | Konverterar enum-typer. |
| static [Unbox](./unbox/)(const SmartPtr\<Object\>\&) | Packar upp strängvärden. |
| static [UnboxStringSafe](./unboxstringsafe/)(const SmartPtr\<Object\>\&) | Packar upp sträng från paketerat värde. |
| static [UnboxToNullable](./unboxtonullable/)(const SmartPtr\<Object\>\&, bool) | Packar upp objekt till nullable-typ. |
| static [UnknownIsNull](./unknownisnull/)(T) | Kontrollerar om okänt typobjekt är nullptr. Överlagring för icke-skalära typer. |
| static [UnknownIsNull](./unknownisnull/)(T) | Kontrollerar om okänt typobjekt är nullptr. Överlagring för skalära typer. |
| static [UnknownToObject](./unknowntoobject/)(T) | Konverterar okänd typ till [Object](../object/), hanterar både smartpekartyper och värdetyp-situationer. |
| static [UnknownToObject](./unknowntoobject/)(const T\&) | Konverterar okänd typ till [Object](../object/), hanterar både smartpekartyper och värdetyp-situationer. |
## Se även

* Class [ObjectType](../objecttype/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
