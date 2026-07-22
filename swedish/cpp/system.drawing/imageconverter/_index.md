---
title: "System::Drawing::ImageConverter klass"
linktitle: "ImageConverter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::ImageConverter klass. Konverterar Image-objekt från en datatyp till en annan. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1300
url: /sv/cpp/system.drawing/imageconverter/
---
## ImageConverter class


Konverterar [Image](../image/) objekt från en datatyp till en annan. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ImageConverter : public System::ComponentModel::TypeConverter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) override | Konverterar objekt till en specifik typ. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Konverterar objekt till en specifik typ. |
| [ImageConverter](./imageconverter/)() | Skapar en ny instans av [ImageConverter](./). |
## Se även

* Class [TypeConverter](../../system.componentmodel/typeconverter/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
