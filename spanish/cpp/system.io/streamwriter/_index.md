---
title: "Clase System::IO::StreamWriter"
linktitle: "StreamWriter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::IO::StreamWriter. Representa un escritor que escribe caracteres en un flujo de bytes. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2300
url: /es/cpp/system.io/streamwriter/
---
## StreamWriter class


Representa un escritor que escribe caracteres en un flujo de bytes. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Close](./close/)() override | Cierra el flujo y libera los recursos adquiridos. |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por el objeto actual y cierra el flujo subyacente. |
| [Flush](./flush/)() override | Vacia el contenido del búfer al flujo subyacente y luego vacía el flujo subyacente. |
| [get_AutoFlush](./get_autoflush/)() const | Devuelve un valor que indica si el [StreamWriter](./) vaciará los datos al flujo subyacente cada vez que se llame al método [StreamWriter::Write](./write/). |
| [get_BaseStream](./get_basestream/)() const | Devuelve un puntero compartido a un objeto que representa el flujo subyacente. |
| [get_Encoding](./get_encoding/)() override | Devuelve la codificación actualmente utilizada. |
| [set_AutoFlush](./set_autoflush/)(bool) | Devuelve un valor que especifica si el [StreamWriter](./) debe vaciar los datos al flujo subyacente cada vez que se llame al método [StreamWriter::Write](./write/). |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres en el flujo subyacente especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes. |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres en el flujo subyacente especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes. |
| [StreamWriter](./streamwriter/)(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres en el flujo subyacente especificado usando la codificación especificada y un búfer del tamaño especificado. Un parámetro indica si el flujo subyacente debe cerrarse cuando se elimina el objeto [StreamWriter](./). |
| [StreamWriter](./streamwriter/)(const String\&) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres en el archivo especificado usando codificación UTF-8 y un búfer con tamaño predeterminado de 1024 bytes. |
| [StreamWriter](./streamwriter/)(const String\&, bool, const EncodingPtr\&) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres en el archivo especificado usando la codificación especificada y un búfer con tamaño predeterminado de 1024 bytes. Un parámetro indica si los datos deben añadirse al archivo o si el archivo debe sobrescribirse. |
| [StreamWriter](./streamwriter/)(const String\&, bool, const EncodingPtr\&, int) | Construye una instancia del objeto [StreamWriter](./) que escribe caracteres en el archivo especificado usando la codificación especificada y el tamaño del búfer. Un parámetro indica si los datos deben añadirse al archivo o si el archivo debe sobrescribirse. |
| [Write](./write/)(char_t) override | Escribe el carácter especificado en el flujo. |
| [Write](./write/)(const String\&) override | Escribe la cadena especificada en el flujo. |
| [Write](./write/)(const SharedPtr\<Object\>\&) override | Escribe la representación en cadena del objeto especificado en el flujo. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&) override | Escribe todos los caracteres del arreglo especificado al flujo. |
| [Write](./write/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado al flujo. |
| [Write](./write/)(const char_t *) override | Escribe la c‑cadena especificada al flujo. |
| [Write](./write/)(const System::SharedPtr\<T\>\&) | Escribe la representación en cadena del objeto especificado en el flujo. |
| [WriteLine](./writeline/)() override | Escribe los caracteres de terminación de línea al flujo. |
| [WriteLine](./writeline/)(const String\&) override | Escribe la cadena especificada seguida de los caracteres de terminación de línea al flujo. |
| [WriteLine](./writeline/)(const SharedPtr\<Object\>\&) override | Escribe la representación en cadena del objeto especificado seguida de los caracteres de terminación de línea al flujo. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&) override | Escribe todos los caracteres del arreglo especificado seguido de los caracteres de terminación de línea al flujo. |
| [WriteLine](./writeline/)(const ArrayPtr\<char_t\>\&, int32_t, int32_t) override | Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado seguido de los caracteres de terminación de línea al flujo. |
| [WriteLine](./writeline/)(const char_t *) override | Escribe la c‑cadena especificada seguida de los caracteres de terminación de línea al flujo. |
| [WriteLine](./writeline/)(const System::SharedPtr\<T\>\&) | Escribe la representación en cadena del objeto especificado seguida de los caracteres de terminación de línea al flujo. |
| [~StreamWriter](./~streamwriter/)() | Destructor. |
## Ver también

* Class [TextWriter](../textwriter/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
