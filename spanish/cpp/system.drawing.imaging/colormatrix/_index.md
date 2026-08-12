---
title: "System::Drawing::Imaging::ColorMatrix clase"
linktitle: "ColorMatrix"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Drawing::Imaging::ColorMatrix. Representa una matriz de 5x5 que contiene las coordenadas del espacio de color RGBAW. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 300
url: /es/cpp/system.drawing.imaging/colormatrix/
---
## ColorMatrix class


Representa una matriz de 5x5 que contiene las coordenadas del espacio de color RGBAW. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class ColorMatrix : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ColorMatrix](./colormatrix/)() | Construye una nueva instancia de la clase [ColorMatrix](./) y la inicializa con los valores de la matriz identidad. |
| [ColorMatrix](./colormatrix/)(const System::ArrayPtr\<System::ArrayPtr\<float\>\>\&) | Construye una nueva instancia de la clase [ColorMatrix](./) y la inicializa con los valores especificados. |
| [get_Matrix00](./get_matrix00/)() const | Devuelve un valor en la fila 0 y la columna 0. |
| [get_Matrix01](./get_matrix01/)() const | Devuelve un valor en la fila 0 y la columna 1. |
| [get_Matrix02](./get_matrix02/)() const | Devuelve un valor en la fila 0 y la columna 2. |
| [get_Matrix03](./get_matrix03/)() const | Devuelve un valor en la fila 0 y la columna 3. |
| [get_Matrix04](./get_matrix04/)() const | Devuelve un valor en la fila 0 y la columna 4. |
| [get_Matrix10](./get_matrix10/)() const | Devuelve un valor en la fila 1 y la columna 0. |
| [get_Matrix11](./get_matrix11/)() const | Devuelve un valor en la fila 1 y la columna 1. |
| [get_Matrix12](./get_matrix12/)() const | Devuelve un valor en la fila 1 y la columna 2. |
| [get_Matrix13](./get_matrix13/)() const | Devuelve un valor en la fila 1 y la columna 3. |
| [get_Matrix14](./get_matrix14/)() const | Devuelve un valor en la fila 1 y la columna 4. |
| [get_Matrix20](./get_matrix20/)() const | Devuelve un valor en la fila 2 y la columna 0. |
| [get_Matrix21](./get_matrix21/)() const | Devuelve un valor en la fila 2 y la columna 1. |
| [get_Matrix22](./get_matrix22/)() const | Devuelve un valor en la fila 2 y la columna 2. |
| [get_Matrix23](./get_matrix23/)() const | Devuelve un valor en la fila 2 y la columna 3. |
| [get_Matrix24](./get_matrix24/)() const | Devuelve un valor en la fila 2 y la columna 4. |
| [get_Matrix30](./get_matrix30/)() const | Devuelve un valor en la fila 3 y la columna 0. |
| [get_Matrix31](./get_matrix31/)() const | Devuelve un valor en la fila 3 y la columna 1. |
| [get_Matrix32](./get_matrix32/)() const | Devuelve un valor en la fila 3 y la columna 2. |
| [get_Matrix33](./get_matrix33/)() const | Devuelve un valor en la fila 3 y la columna 3. |
| [get_Matrix34](./get_matrix34/)() const | Devuelve un valor en la fila 3 y la columna 4. |
| [get_Matrix40](./get_matrix40/)() const | Devuelve un valor en la fila 4 y la columna 0. |
| [get_Matrix41](./get_matrix41/)() const | Devuelve un valor en la fila 4 y la columna 1. |
| [get_Matrix42](./get_matrix42/)() const | Devuelve un valor en la fila 4 y la columna 2. |
| [get_Matrix43](./get_matrix43/)() const | Devuelve un valor en la fila 4 y la columna 3. |
| [get_Matrix44](./get_matrix44/)() const | Devuelve un valor en la fila 4 y la columna 4. |
| [idx_get](./idx_get/)(int, int) | Devuelve un valor en la fila especificada y la columna especificada. |
| [idx_set](./idx_set/)(int, int, float) | Establece el valor especificado en la ubicación indicada en la matriz. |
| [set_Matrix00](./set_matrix00/)(float) | Establece un valor en la fila 0 y la columna 0. |
| [set_Matrix01](./set_matrix01/)(float) | Establece un valor en la fila 0 y la columna 1. |
| [set_Matrix02](./set_matrix02/)(float) | Establece un valor en la fila 0 y la columna 2. |
| [set_Matrix03](./set_matrix03/)(float) | Establece un valor en la fila 0 y la columna 3. |
| [set_Matrix04](./set_matrix04/)(float) | Establece un valor en la fila 0 y la columna 4. |
| [set_Matrix10](./set_matrix10/)(float) | Establece un valor en la fila 1 y la columna 0. |
| [set_Matrix11](./set_matrix11/)(float) | Establece un valor en la fila 1 y la columna 1. |
| [set_Matrix12](./set_matrix12/)(float) | Establece un valor en la fila 1 y la columna 2. |
| [set_Matrix13](./set_matrix13/)(float) | Establece un valor en la fila 1 y la columna 3. |
| [set_Matrix14](./set_matrix14/)(float) | Establece un valor en la fila 1 y la columna 4. |
| [set_Matrix20](./set_matrix20/)(float) | Establece un valor en la fila 2 y la columna 0. |
| [set_Matrix21](./set_matrix21/)(float) | Establece un valor en la fila 2 y la columna 1. |
| [set_Matrix22](./set_matrix22/)(float) | Establece un valor en la fila 2 y la columna 2. |
| [set_Matrix23](./set_matrix23/)(float) | Establece un valor en la fila 2 y la columna 3. |
| [set_Matrix24](./set_matrix24/)(float) | Establece un valor en la fila 2 y la columna 4. |
| [set_Matrix30](./set_matrix30/)(float) | Establece un valor en la fila 3 y la columna 0. |
| [set_Matrix31](./set_matrix31/)(float) | Establece un valor en la fila 3 y la columna 1. |
| [set_Matrix32](./set_matrix32/)(float) | Establece un valor en la fila 3 y la columna 2. |
| [set_Matrix33](./set_matrix33/)(float) | Establece un valor en la fila 3 y la columna 3. |
| [set_Matrix34](./set_matrix34/)(float) | Establece un valor en la fila 3 y la columna 4. |
| [set_Matrix40](./set_matrix40/)(float) | Establece un valor en la fila 4 y la columna 0. |
| [set_Matrix41](./set_matrix41/)(float) | Establece un valor en la fila 4 y la columna 1. |
| [set_Matrix42](./set_matrix42/)(float) | Establece un valor en la fila 4 y la columna 2. |
| [set_Matrix43](./set_matrix43/)(float) | Establece un valor en la fila 4 y la columna 3. |
| [set_Matrix44](./set_matrix44/)(float) | Establece un valor en la fila 4 y la columna 4. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
