---
title: "Clase System::Text::RegularExpressions::Regex"
linktitle: "Regex"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Text::RegularExpressions::Regex. Expresión regular que sigue una sintaxis similar a C#. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 800
url: /es/cpp/system.text.regularexpressions/regex/
---
## Regex class


Expresión regular que sigue una sintaxis similar a C#. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class Regex : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Escape](./escape/)(const String\&) | Escapa caracteres especiales para usar la cadena como parte del patrón. |
| [get_MatchTimeout](./get_matchtimeout/)() | Obtiene el tiempo de espera de coincidencia. |
| [get_Options](./get_options/)() | Obtiene las opciones de la expresión regular. |
| [get_RightToLeft](./get_righttoleft/)() | Comprueba si la coincidencia se realiza en modo de derecha a izquierda. |
| [IsMatch](./ismatch/)(const String\&, int) | Coincide la expresión regular contra una cadena. |
| static [IsMatch](./ismatch/)(const String\&, const String\&, RegexOptions, TimeSpan, int) | Comprueba si la cadena coincide con el patrón. |
| [Match](./match/)(const String\&) | Coincide la expresión regular contra una cadena. |
| [Match](./match/)(const String\&, int, int) | Coincide la expresión regular contra una cadena. |
| static [Match](./match/)(const String\&, const String\&, RegexOptions, TimeSpan, int, int) | Coincide cadena y patrón. |
| [Matches](./matches/)(const String\&, int) | Obtiene todas las coincidencias de la expresión regular en una cadena dada mediante coincidencias repetidas. |
| static [Matches](./matches/)(const String\&, const String\&, RegexOptions, TimeSpan, int, int) | Obtiene todas las coincidencias entre la cadena y el patrón. |
| [Regex](./regex/)() | Construye una expresión regular vacía. |
| [Regex](./regex/)(const String\&) | Constructor. |
| [Regex](./regex/)(const String\&, RegexOptions) | Constructor. |
| [Regex](./regex/)(const String\&, RegexOptions, TimeSpan) | Constructor. |
| [Replace](./replace/)(const String\&, const String\&) | Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo. |
| [Replace](./replace/)(const String\&, const char_t *) | Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo. |
| static [Replace](./replace/)(const String\&, const char_t *, const char_t *) | Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo. |
| static [Replace](./replace/)(const String\&, const String\&, const char_t *) | Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo. |
| [Replace](./replace/)(const String\&, const MatchEvaluator\&) | Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por el delegado. |
| [Replace](./replace/)(const String\&, const MatchEvaluator\&, int) | Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por el delegado. |
| [Replace](./replace/)(const String\&, const MatchEvaluator\&, int, int) | Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por el delegado. |
| static [Replace](./replace/)(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) | Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por el delegado (función estática). |
| static [Replace](./replace/)(const String\&, const String\&, const String\&, RegexOptions) | Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo. |
| [Replace](./replace/)(const String\&, const String\&, int) | Reemplaza subcadenas en la cadena. No implementado. |
| [Replace](./replace/)(const String\&, const String\&, int, int) | Reemplaza subcadenas en la cadena. No implementado. |
| static [Replace](./replace/)(const String\&, const String\&, const String\&) | Reemplaza coincidencias de la expresión regular. |
| static [Replace](./replace/)(const String\&, const String\&, const MatchEvaluator\&) | Reemplaza coincidencias de la expresión regular. |
| [Split](./split/)(const String\&) | Divide la cadena por coincidencias de la expresión regular. |
| [Split](./split/)(const String\&, int) | Divide la cadena por coincidencias de la expresión regular. |
| [Split](./split/)(const String\&, int, int) | Divide una cadena de entrada un número máximo especificado de veces en una matriz de subcadenas, en las posiciones definidas por una expresión regular especificada en el constructor [Regex](./). La búsqueda del patrón de expresión regular comienza en una posición de carácter especificada en la cadena de entrada. |
| static [Split](./split/)(const String\&, const String\&, RegexOptions, TimeSpan) | Divide la cadena por la expresión regular. |
| static [Split](./split/)(const String\&, const String\&, int, RegexOptions, TimeSpan) | Divide la cadena por la expresión regular. |
| [ToString](./tostring/)() const override | Convierte la expresión regular a cadena. |
| static [Unescape](./unescape/)(const String\&) | Desescapa los caracteres especiales en la cadena usados como parte del patrón. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [InfiniteMatchTimeout](./infinitematchtimeout/) | Valor de tiempo de espera especial para desactivar la interrupción de coincidencia por tiempo de espera. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
