---
title: "System::Drawing::Imaging::Metafile class"
linktitle: "Metafile"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Imaging::Metafile class. Representerar en grafisk metafil. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1200
url: /sv/cpp/system.drawing.imaging/metafile/
---
## Metafile class


Representerar en grafisk metafil. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Metafile : public System::Drawing::Image
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Returnerar en kopia av det aktuella objektet. |
| [get_Height](./get_height/)() const override | Returnerar bildens höjder i pixlar. |
| [get_PixelFormat](./get_pixelformat/)() const override | Returnerar ett värde som indikerar pixelformatet. |
| [get_RawFormat](./get_rawformat/)() const override | Returnerar ett värde som indikerar bildformatet. |
| [get_Width](./get_width/)() const override | Returnerar bildens bredd i pixlar. |
| [GetHenhmetafile](./gethenhmetafile/)() | INTE IMPLEMENTERAD. |
| [GetMetafileHeader](./getmetafileheader/)() | Returnerar ett huvud som är associerat med det aktuella objektet. |
| [Metafile](./metafile/)(const System::String\&) | INTE IMPLEMENTERAD. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&) | INTE IMPLEMENTERAD. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, EmfType) | INTE IMPLEMENTERAD. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr) | INTE IMPLEMENTERAD. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, Rectangle, MetafileFrameUnit, EmfType) | INTE IMPLEMENTERAD. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, RectangleF, MetafileFrameUnit, EmfType) | INTE IMPLEMENTERAD. |
| [Metafile](./metafile/)(IntPtr, EmfType) | INTE IMPLEMENTERAD. |
| [PlayRecord](./playrecord/)(EmfPlusRecordType, int32_t, int32_t, System::ByteArrayPtr) | INTE IMPLEMENTERAD. |
| virtual [~Metafile](./~metafile/)() | Destruktor. |
## Se även

* Class [Image](../../system.drawing/image/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
