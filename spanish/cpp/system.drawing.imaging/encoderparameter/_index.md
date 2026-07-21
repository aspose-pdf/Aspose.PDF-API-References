---
title: "Clase System::Drawing::Imaging::EncoderParameter"
linktitle: "EncoderParameter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Imaging::EncoderParameter. Sirve como un contenedor utilizado para pasar valores a un codificador de imágenes. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 600
url: /es/cpp/system.drawing.imaging/encoderparameter/
---
## EncoderParameter class


Sirve como un contenedor utilizado para pasar valores a un codificador de imágenes. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class EncoderParameter : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [EncoderParameter](./encoderparameter/)() | Construye una nueva instancia de la clase [EncoderParameter](./). |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, uint8_t, bool) | Construye una nueva instancia de la clase [EncoderParameter](./). |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int16_t) | Construye una nueva instancia de la clase [EncoderParameter](./). |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int64_t) | Construye una nueva instancia de la clase [EncoderParameter](./). |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t) | Construye una nueva instancia de la clase [EncoderParameter](./). |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t, int32_t) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una fracción. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int64_t, int64_t) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa un rango de valores enteros. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t, int32_t, int32_t, int32_t) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa un rango de fracciones. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const String\&) | Construye una nueva instancia de la clase [EncoderParameter](./). |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<uint8_t\>\&, bool) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de valores. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int16_t\>\&) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de valores. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de valores. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de fracciones. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&, const ArrayPtr\<int64_t\>\&) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de rangos de enteros. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa una matriz de rangos de fracciones. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int, EncoderParameterValueType, void *) | Construye una nueva instancia de la clase [EncoderParameter](./) que representa el número especificado de valores del tipo especificado que se leen del búfer especificado. |
| [get_Encoder](./get_encoder/)() const | Devuelve el objeto [Encoder](../encoder/) asociado con el objeto [EncoderParameter](./) actual. |
| [get_NumberOfValues](./get_numberofvalues/)() const | Devuelve el número de valores representados por el objeto actual. |
| [get_Type](./get_type/)() const | Devuelve el tipo de los valores representados por el objeto actual. |
| [set_Encoder](./set_encoder/)(const EncoderPtr\&) | Asocia el objeto [Encoder](../encoder/) especificado con el objeto [EncoderParameter](./) actual. |
| [~EncoderParameter](./~encoderparameter/)() | Destructor. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
