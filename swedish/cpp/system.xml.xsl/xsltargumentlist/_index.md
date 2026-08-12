---
title: "System::Xml::Xsl::XsltArgumentList-klass"
linktitle: "XsltArgumentList"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::XsltArgumentList-klass. Innehåller ett variabelt antal argument som antingen är XSLT-parametrar eller extensionsobjekt i C++."
type: docs
weight: 400
url: /sv/cpp/system.xml.xsl/xsltargumentlist/
---
## XsltArgumentList class


Innehåller ett variabelt antal argument som antingen är XSLT-parametrar eller extensionsobjekt.

```cpp
class XsltArgumentList : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddExtensionObject](./addextensionobject/)(const String\&, const SharedPtr\<Object\>\&) | Lägger till ett nytt objekt i [XsltArgumentList](./) och associerar det med namnrymdens URI. |
| [AddParam](./addparam/)(const String\&, const String\&, const SharedPtr\<Object\>\&) | Lägger till en parameter i [XsltArgumentList](./) och associerar den med det namnrymdskvalificerade namnet. |
| [Clear](./clear/)() | Tar bort alla parametrar och extensionsobjekt från [XsltArgumentList](./). |
| [GetExtensionObject](./getextensionobject/)(const String\&) | Returnerar objektet som är associerat med den angivna namnrymden. |
| [GetParam](./getparam/)(const String\&, const String\&) | Returnerar parametern som är associerad med det namnrymdskvalificerade namnet. |
| [RemoveExtensionObject](./removeextensionobject/)(const String\&) | Tar bort objektet med namnrymdens URI från [XsltArgumentList](./). |
| [RemoveParam](./removeparam/)(const String\&, const String\&) | Tar bort parametern från [XsltArgumentList](./). |
| [XsltArgumentList](./xsltargumentlist/)() | Skapar en ny instans av [XsltArgumentList](./). |
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
