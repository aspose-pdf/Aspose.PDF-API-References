---
title: "System::Security::SecurityElement klass"
linktitle: "SecurityElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::SecurityElement klass. XML‑objektmodell för kodning av säkerhetsobjekt. Inte implementerad. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.security/securityelement/
---
## SecurityElement class


XML‑objektmodell för kodning av säkerhetsobjekt. Inte implementerad. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SecurityElement : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddAttribute](./addattribute/)(const String\&, const String\&) | Lägger till attribut till taggen. |
| [AddChild](./addchild/)(SecurityElement) | Lägger till underordnad tagg. |
| [Attribute](./attribute/)(const String\&) | Hämtar attributvärde. |
| [Copy](./copy/)() | Klonar tagg. |
| [Equal](./equal/)(SecurityElement) | Kontrollerar om parametrarna är lika. |
| static [Escape](./escape/)(const String\&) | Escapar tecken i XML‑sträng. |
| static [FromString](./fromstring/)(const String\&) | Skapar element från XML‑kod. |
| [get_Attributes](./get_attributes/)() | Hämtar tagg‑attribut. |
| [get_Children](./get_children/)() | Hämtar taggens underordnade objekt. |
| [get_Tag](./get_tag/)() | Hämtar taggnamn. |
| [get_Text](./get_text/)() | Hämtar taggens inre text. |
| static [IsValidAttributeName](./isvalidattributename/)(const String\&) | Kontrollerar om attributnamnet är giltigt. |
| static [IsValidAttributeValue](./isvalidattributevalue/)(const String\&) | Kontrollerar om attributvärdet är giltigt. |
| static [IsValidTag](./isvalidtag/)(const String\&) | Kontrollerar om taggen är giltig. |
| static [IsValidText](./isvalidtext/)(const String\&) | Kontrollerar om texten är giltig. |
| [SearchForChildByTag](./searchforchildbytag/)(const String\&) | Hämtar underordnad tagg efter namn. |
| [SearchForTextOfTag](./searchfortextoftag/)(const String\&) | Hämtar underordnad taggs inre text efter taggnamn. |
| [SecurityElement](./securityelement/)(const String\&) | Konstruktor. |
| [SecurityElement](./securityelement/)(const String\&, const String\&) | Konstruktor. |
| [set_Attributes](./set_attributes/)(System::Collections::Generic::Dictionary\<String, String\>) | Sätter tagg‑attribut. |
| [set_Children](./set_children/)(System::Collections::Generic::List\<SecurityElement\>) | Sätter taggens underordnade objekt. |
| [set_Tag](./set_tag/)(const String\&) | Ställer in taggnamn. |
| [set_Text](./set_text/)(const String\&) | Ställer in taggens inre text. |
| [ToString](./tostring/)() const override | Konverterar tagg till sträng. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security](../)
* Library [Aspose.PDF for C++](../../)
