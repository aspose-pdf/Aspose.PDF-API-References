---
title: "System::Drawing::ImageFormatConverter klass"
linktitle: "ImageFormatConverter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::ImageFormatConverter-klass. Konverterar ImageFormat-objekt från en datatyp till en annan. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1400
url: /sv/cpp/system.drawing/imageformatconverter/
---
## ImageFormatConverter class


Konverterar ImageFormat-objekt från en datatyp till en annan. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ImageFormatConverter : public System::ComponentModel::TypeConverter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ConvertFrom](./convertfrom/)(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&) override | Konverterar objekt. |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<System::Object\>\&) | Konverterar objekt. |
| virtual [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) | Konverterar objekt. |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) | Konverterar sträng till objekt. |
| [ConvertTo](./convertto/)(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) override | Konverterar objekt till en specifik typ. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Konverterar objekt till en specifik typ. |
| virtual [ConvertTo](./convertto/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Konverterar objekt till en specifik typ. |
| [ImageFormatConverter](./imageformatconverter/)() | Skapar en ny instans av [ImageFormatConverter](./). |
## Se även

* Class [TypeConverter](../../system.componentmodel/typeconverter/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
