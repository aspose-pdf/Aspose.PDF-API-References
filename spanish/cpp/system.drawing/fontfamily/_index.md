---
title: "Clase System::Drawing::FontFamily"
linktitle: "FontFamily"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::FontFamily. Representa un grupo de tipografías que comparten un diseño básico similar. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++."
type: docs
weight: 900
url: /es/cpp/system.drawing/fontfamily/
---
## FontFamily class


Representa un grupo de tipografías que comparten un diseño básico similar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FontFamily : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() | Devuelve una copia del objeto [FontFamily](./) actual. |
| [Dispose](./dispose/)() | Libera todos los recursos del sistema operativo adquiridos por el objeto actual. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determina si el objeto actual y el objeto especificado son idénticos. |
| [FontFamily](./fontfamily/)(const String\&) | Construye una nueva instancia de la clase [FontFamily](./) que representa una familia de fuentes con el nombre especificado. |
| [FontFamily](./fontfamily/)(const String\&, const SharedPtr\<Text::FontCollection\>\&) | Construye una nueva instancia de [FontFamily](./) en la FontCollection especificada con el nombre especificado. |
| [FontFamily](./fontfamily/)(Text::GenericFontFamilies) | Construye una nueva instancia de [FontFamily](./) a partir de la familia de fuentes genérica especificada. |
| static [get_Families](./get_families/)() | Devuelve una matriz que contiene todos los objetos [FontFamily](./) asociados con el contexto gráfico actual. |
| static [get_GenericMonospace](./get_genericmonospace/)() | Devuelve un objeto [FontFamily](./) que representa una familia de fuentes genérica monoespaciada. |
| static [get_GenericSansSerif](./get_genericsansserif/)() | Devuelve un objeto [FontFamily](./) que representa una familia de fuentes genérica sans serif. |
| static [get_GenericSerif](./get_genericserif/)() | Devuelve un objeto [FontFamily](./) que representa una familia de fuentes genérica con serif. |
| [get_Name](./get_name/)() const | Devuelve el nombre de la familia de fuentes representada por el objeto actual. |
| [GetCellAscent](./getcellascent/)(FontStyle) | Devuelve la ascensión de celda de la familia de fuentes representada por el objeto actual para el estilo de fuente especificado. |
| [GetCellDescent](./getcelldescent/)(FontStyle) | Devuelve la descendencia de celda de la familia de fuentes representada por el objeto actual para el estilo de fuente especificado. |
| [GetEmHeight](./getemheight/)(FontStyle) | Devuelve la altura del cuadrado em en unidades de diseño de fuente para el estilo especificado. |
| [GetLineSpacing](./getlinespacing/)(FontStyle) | Devuelve el interlineado de la familia de fuentes representada por el objeto actual para el estilo de fuente especificado. |
| [GetName](./getname/)(int) const | Devuelve el nombre de la familia de fuentes representada por el objeto actual. |
| [IsStyleAvailable](./isstyleavailable/)(FontStyle) | Determina si el estilo de fuente especificado está disponible. |
| virtual [~FontFamily](./~fontfamily/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
