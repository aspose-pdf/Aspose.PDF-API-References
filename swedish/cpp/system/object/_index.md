---
title: "System::Object-klass"
linktitle: "Object"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Object-klass. Basklass som möjliggör användning av metoder som finns tillgängliga för System.Object-klassen i C#. Alla icke-triviala klasser som används i den översatta miljön bör ärva den i C++."
type: docs
weight: 5000
url: /sv/cpp/system/object/
---
## Object class


Basklass som möjliggör användning av metoder som finns tillgängliga för [System.Object](./)-klassen i C#. Alla icke-triviala klasser som används i den översatta miljön bör ärva den.

```cpp
class Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Equals](./equals/)(ptr) | Jämför objekt med C# [Object.Equals](./equals/)-semantik. |
| static [Equals](./equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static [Equals](./equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static [Equals](./equals/)(float const\&, float const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN‑värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static [Equals](./equals/)(double const\&, double const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN‑värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [GetCounter](./getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual [GetHashCode](./gethashcode/)() const | Analog till C# [Object.GetHashCode()](./gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual [GetType](./gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](./gettype/)-anrop. |
| virtual [Is](./is/)(const TypeInfo\&) const | Kontrollera om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| [Lock](./lock/)() | Implementerar C# lock()-satsen för låsning. Anropa direkt eller använd [LockContext](../lockcontext/) sentinelobjekt. |
| virtual [MemberwiseClone](./memberwiseclone/)() const | Analog till C#-metoden [Object.MemberwiseClone()](./memberwiseclone/). Möjliggör kloning av anpassade typer. |
| [Object](./object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](./object/)(Object const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [operator=](./operator=/)(Object const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static [ReferenceEquals](./referenceequals/)(ptr const\&, ptr const\&) | Jämför objekt efter referens. |
| static [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| [ReferenceEquals](./referenceequals/)(String const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](./referenceequals/) för fallet med sträng och nullptr. |
| [ReferenceEquals](./referenceequals/)(String const\&, String const\&) | Specialisering av [Object::ReferenceEquals](./referenceequals/) för fallet med strängar. |
| [RemovedSharedRefs](./removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| virtual [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) | Ställ in n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| [SharedCount](./sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [SharedRefAdded](./sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [ToString](./tostring/)() const | Analog till C#-metoden [Object.ToString()](./tostring/). Möjliggör konvertering av anpassade objekt till sträng. |
| static [Type](./type/)() | Implementerar C#-konstruktionen typeof([System.Object](./)). |
| [Unlock](./unlock/)() | Implementerar C# lock()-satsen för upplåsning. Anropa direkt eller använd [LockContext](../lockcontext/) sentinelobjekt. |
| [WeakRefAdded](./weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [WeakRefRemoved](./weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [~Object](./~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ptr](./ptr/) | Alias för smart pekartyp. |
## Anmärkningar


Förutom metoderna som finns i C#-klassen [System.Object](./) möjliggör den även stöd för vissa koncept som är specifika för den översatta kodmiljön. Detta inkluderar referensräkning som används av smarta pekarklasser ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) samt andra tjänster relaterade till minneshantering, felsökning osv.

Varje [Object](./) har två referensräknare: en delad referensräknare och en svag referensräknare. Den svaga referensräknaren lagras alltid i en fristående datastruktur snarare än i själva [Object](./), vilket möjliggör att svaga pekare överlever det refererade objektet. Den smarta referensräknaren lagras antingen i objektet självt eller i samma fristående struktur, beroende på makrot ENABLE_EXTERNAL_REFCOUNT. Som standard är den aktiverad i debug‑byggen och inaktiverad i release‑byggen. Om smart pekarräknaren lagras i objektet självt skapas den fristående datastrukturen endast om svaga pekare till objektet finns. Annars skapas den tillsammans med objektet självt.

Alla smarta pekare använder dessa två referensräknare och bidrar till samma och enda ägandegrupp.

Om en [Object](./)-subklass skapas på stacken får inga smarta pekare till den skapas, annars uppstår ett problem med stackdeletion.

Denna typ kan allokeras antingen på stacken som värdetyp eller på heapen med funktionen [System::MakeObject()](../makeobject/). När objektet väl är allokerat får man aldrig blanda dessa två användningsfall: att ha [SmartPtr](../smartptr/)-pekare till stackallokerade objekt är strikt förbjudet.
## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
