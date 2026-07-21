---
title: "System::Drawing::Imaging::Encoder class"
linktitle: "Encoder"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Drawing::Imaging::Encoder class. Representa un GUID que está asociado a un conjunto de parámetros del codificador de imágenes. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 500
url: /es/cpp/system.drawing.imaging/encoder/
---
## Encoder class


Representa un GUID que está asociado a un conjunto de parámetros del codificador de imágenes. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class Encoder : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Encoder](./encoder/)(const Guid\&) | Construye una nueva instancia de la clase [Encoder](./). |
| [get_Guid](./get_guid/)() const | Devuelve un GUID que especifica un conjunto de parámetros del codificador de imágenes que representa el objeto actual. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [ChrominanceTable](./chrominancetable/) | Una instancia de la clase [Encoder](./) que representa la categoría de parámetro de tabla de crominancia. |
| static [ColorDepth](./colordepth/) | Una instancia de la clase [Encoder](./) que representa la categoría de parámetro de profundidad de color. |
| static [Compression](./compression/) | Una instancia de la clase [Encoder](./) que representa la categoría de parámetro de compresión. |
| static [LuminanceTable](./luminancetable/) | Una instancia de la clase [Encoder](./) que representa la categoría de parámetro de tabla de luminancia. |
| static [Quality](./quality/) | Una instancia de la clase [Encoder](./) que representa la categoría de parámetro de calidad. |
| static [RenderMethod](./rendermethod/) | Una instancia de la clase [Encoder](./) que representa la categoría de parámetro de método de renderizado. |
| static [SaveFlag](./saveflag/) | Una instancia de la clase [Encoder](./) que representa la categoría de parámetro de bandera de guardado. |
| static [ScanMethod](./scanmethod/) | Una instancia de la clase [Encoder](./) que representa la categoría de parámetro de método de escaneo. |
| static [Transformation](./transformation/) | Una instancia de la clase [Encoder](./) que representa la categoría de parámetro de transformación. |
| static [Version](./version/) | Una instancia de la clase [Encoder](./) que representa la categoría de parámetro de versión. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
