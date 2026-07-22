---
title: "System::Version‑klass"
linktitle: "Version"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Version‑klass. Representerar ett versionsnummer. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr‑klassen för att hantera objekt av denna typ i C++."
type: docs
weight: 7600
url: /sv/cpp/system/version/
---
## Version class


Representerar ett versionsnummer. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/)‑klassen för att hantera objekt av denna typ.

```cpp
class Version
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CompareTo](./compareto/)(const Version\&) const | Jämför versionerna som representeras av det aktuella objektet och det angivna objektet. |
| [Equals](./equals/)(const Version\&) const | Avgör om versionsnumren som representeras av det aktuella och det angivna objektet är lika. |
| [get_Build](./get_build/)() const | Returnerar byggnumret. |
| [get_Major](./get_major/)() const | Returnerar huvudversionen. |
| [get_MajorRevision](./get_majorrevision/)() const | Returnerar det högsta 16‑bit‑värdet av revisionsnumret. |
| [get_Minor](./get_minor/)() const | Returnerar underversionen. |
| [get_MinorRevision](./get_minorrevision/)() const | Returnerar det lägsta 16‑bit‑värdet av revisionsnumret. |
| [get_Revision](./get_revision/)() const | Returnerar revisionsnumret. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| static [Parse](./parse/)(const String\&) | Konverterar strängrepresentationen av ett versionsnummer till en motsvarande instans av [Version](./)‑klassen. |
| [ToString](./tostring/)() const | Returnerar strängrepresentationen av versionsnumret som representeras av det aktuella objektet. |
| [ToString](./tostring/)(int) const | Returnerar strängrepresentationen av det angivna antalet sektioner av versionsnumret som representeras av det aktuella objektet. |
| [Version](./version/)(int, int, int, int) | Skapar en instans som representerar de angivna huvud-, under-, bygg- och revisionsvärdena. |
| [Version](./version/)(int, int, int) | Skapar en instans som representerar de angivna huvud-, under- och byggvärdena. |
| [Version](./version/)(int, int) | Skapar en instans som representerar de angivna huvud- och värdena. |
| [Version](./version/)(const String\&) | Skapar en instans som representerar versionsnumret som en sträng. |
| [Version](./version/)() | Skapar en instans som representerar versionsnumret 0.0.-1.-1. |
## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
