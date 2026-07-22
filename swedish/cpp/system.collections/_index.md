---
title: "System::Collections namnrymd"
linktitle: "System::Collections"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder System::Collections namnrymd i C++."
type: docs
weight: 2900
url: /sv/cpp/system.collections/
---



## Klasser

| Klass | Beskrivning |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) av bitar som kan adresseras med index. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [BitArrayPtr](./bitarrayptr/) | Pekare till [BitArray](./bitarray/). Denna typ är en pekare för att hantera radering av andra objekt. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens. |
| [CollectionBase](./collectionbase/) | Tillhandahåller en abstrakt basklass för en starkt typad samling. |
| [ICollection](./icollection/) | Definierar ett icke-generiskt samlingsgränssnitt. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) är basgränssnittet för alla icke-generiska samlingar som kan enumereras. |
| [IEnumerator](./ienumerator/) | Gränssnitt för en enumerator som kan användas för att iterera genom vissa element. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Wrapper som skapar en icke-generisk [IEnumerator](./ienumerator/) implementation över den generiska iteratorn [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper för referenstyper. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Wrapper som skapar en icke-generisk [IEnumerator](./ienumerator/) implementation över den generiska iteratorn [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper för värdetyper. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) Representerar en icke-generisk samling av objekt som kan nås individuellt via index. |
| [IListImplRefType](./ilistimplreftype/) | Stub som implementerar [System::Collections::IList](./ilist/) gränssnittet på ett [System::Collections::Generic::List](../system.collections.generic/list/) objekt. Implementation för referenstyper. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub som implementerar [System::Collections::IList](./ilist/) gränssnittet på ett [System::Collections::Generic::List](../system.collections.generic/list/) objekt. Implementation för värdetyper. |
| [IListWrapper](./ilistwrapper/) | Gränssnitt för att stödja kastning från generisk till icke-generisk samling. |
| [Invalidatable](./invalidatable/) | Klass som möjliggör att spåra tillståndet för sina ättlingar via [InvalidatableTracker](./invalidatabletracker/) objekt. |
| [InvalidatableTracker](./invalidatabletracker/) | Klass som implementerar spårare för [Invalidatable](./invalidatable/) objekt. |
