---
title: "Clase System::IO::StreamReader"
linktitle: "StreamReader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::StreamReader. Representa un lector que lee caracteres de un flujo de bytes. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() . Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarla a funciones como argumento en C++."
type: docs
weight: 2200
url: /es/cpp/system.io/streamreader/
---
## StreamReader class


Representa un lector que lee caracteres de un flujo de bytes. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class StreamReader : public System::IO::TextReader
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Close](./close/)() override | Cierra los flujos actual y subyacente. |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por el objeto actual y cierra el flujo subyacente. |
| [get_BaseStream](./get_basestream/)() const | Devuelve un puntero compartido a un objeto que representa el flujo subyacente. |
| [get_CurrentEncoding](./get_currentencoding/)() | Devuelve la codificación actualmente utilizada. |
| [get_EndOfStream](./get_endofstream/)() | Devuelve un valor que indica si se ha alcanzado el final del flujo. |
| [Peek](./peek/)() override | Lee un solo carácter del flujo sin cambiar el cursor de lectura del flujo. |
| [Read](./read/)() override | Lee un solo carácter del flujo. |
| [Read](./read/)(ArrayPtr\<char_t\>, int, int) override | Lee el número especificado de caracteres del flujo, los convierte a codificación UTF-16 y escribe los caracteres UTF-16 resultantes en la matriz de caracteres especificada, comenzando en la posición indicada. |
| [ReadLine](./readline/)() override | Lee caracteres del flujo hasta el final de la línea actual. |
| [ReadToEnd](./readtoend/)() override | Lee caracteres del flujo hasta el final del flujo. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, bool) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
| [StreamReader](./streamreader/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer del tamaño especificado. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
| [StreamReader](./streamreader/)(const System::String\&) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del archivo especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 4096 bytes. |
| [StreamReader](./streamreader/)(const System::String\&, bool) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del archivo especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 4096 bytes. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del archivo especificado usando la codificación especificada y un búfer con tamaño predeterminado de 4096 bytes. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&, bool) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 4096 bytes. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
| [StreamReader](./streamreader/)(const System::String\&, const EncodingPtr\&, bool, int) | Construye una instancia del objeto [StreamReader](./) que lee caracteres del archivo especificado usando la codificación especificada y un búfer del tamaño especificado. Un parámetro especifica si debe habilitarse la detección de marca de orden de bytes. |
| [~StreamReader](./~streamreader/)() | Destructor. |
## Ver también

* Class [TextReader](../textreader/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
