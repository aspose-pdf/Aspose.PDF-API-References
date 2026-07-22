---
title: "System::Xml::Xsl::XsltSettings class"
linktitle: "XsltSettings"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::XsltSettings class. Anger XSLT-funktionerna som ska stödjas under körning av XSLT-stilmallen i C++."
type: docs
weight: 800
url: /sv/cpp/system.xml.xsl/xsltsettings/
---
## XsltSettings class


Specificerar XSLT-funktionerna som ska stödjas under exekveringen av XSLT-stilmallen.

```cpp
class XsltSettings : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [get_Default](./get_default/)() | Returnerar ett [XsltSettings](./)-objekt med standardinställningar. Stöd för XSLT **document()**-funktionen och inbäddade skriptblock är inaktiverat. |
| [get_EnableDocumentFunction](./get_enabledocumentfunction/)() | Returnerar ett värde som indikerar om stöd för XSLT **document()**-funktionen ska aktiveras. |
| [get_EnableScript](./get_enablescript/)() | Returnerar ett värde som indikerar om stöd för inbäddade skriptblock ska aktiveras. |
| static [get_TrustedXslt](./get_trustedxslt/)() | Returnerar ett [XsltSettings](./)-objekt som möjliggör stöd för XSLT **document()**-funktionen och inbäddade skriptblock. |
| [set_EnableDocumentFunction](./set_enabledocumentfunction/)(bool) | Ställer in ett värde som indikerar om stöd för XSLT **document()**-funktionen ska aktiveras. |
| [set_EnableScript](./set_enablescript/)(bool) | Ställer in ett värde som indikerar om stöd för inbäddade skriptblock ska aktiveras. |
| [XsltSettings](./xsltsettings/)() | Initierar en ny instans av [XsltSettings](./)-klassen med standardinställningar. |
| [XsltSettings](./xsltsettings/)(bool, bool) | Initierar en ny instans av [XsltSettings](./)-klassen med de angivna inställningarna. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
