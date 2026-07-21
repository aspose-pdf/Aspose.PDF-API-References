---
title: "System::IO::BinaryReader class"
linktitle: "BinaryReader"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::BinaryReader class. Representa un lector que lee tipos de datos primitivos como datos binarios en una codificación particular. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use este puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 800
url: /es/cpp/system.io/binaryreader/
---
## BinaryReader class


Representa un lector que lee tipos de datos primitivos como datos binarios en una codificación particular. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use este puntero para pasarlo a funciones como argumento.

```cpp
class BinaryReader : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&) | Construye una instancia de la clase [BinaryReader](./) que lee datos del flujo especificado usando codificación UTF-8. |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) | Construye una instancia de la clase [BinaryReader](./) que lee datos del flujo especificado usando la codificación especificada. |
| [BinaryReader](./binaryreader/)(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) | Construye una instancia de la clase [BinaryReader](./) que lee datos del flujo especificado usando la codificación especificada. |
| virtual [Close](./close/)() | Cierra el objeto [BinaryReader](./) actual y el flujo de entrada subyacente. |
| [Dispose](./dispose/)() override | Libera todos los recursos utilizados por el objeto actual y cierra el flujo subyacente. |
| virtual [get_BaseStream](./get_basestream/)() | Devuelve el flujo de entrada. |
| virtual [PeekChar](./peekchar/)() | Lee un solo carácter del flujo de entrada sin cambiar el cursor de lectura del flujo. |
| virtual [Read](./read/)() | Lee un solo carácter del flujo de entrada. |
| virtual [Read](./read/)(ArrayPtr\<uint8_t\>, int, int) | Lee la cantidad especificada de bytes del flujo de entrada y los escribe en la matriz de bytes especificada. |
| virtual [Read](./read/)(ArrayPtr\<char_t\>, int, int) | Lee la cantidad especificada de caracteres del flujo de entrada, los convierte a codificación UTF-16 y escribe los caracteres UTF-16 resultantes en la matriz de caracteres especificada comenzando en la posición indicada. |
| virtual [ReadBoolean](./readboolean/)() | Lee un solo byte del flujo de entrada y devuelve su representación booleana. |
| virtual [ReadByte](./readbyte/)() | Lee un solo byte del flujo de entrada. |
| virtual [ReadBytes](./readbytes/)(int) | Lee la cantidad especificada de bytes del flujo de entrada. |
| virtual [ReadChar](./readchar/)() | Lee un solo carácter del flujo de entrada. |
| virtual [ReadChars](./readchars/)(int) | Lee la cantidad especificada de caracteres del flujo de entrada y los devuelve en codificación UTF-16. |
| virtual [ReadDecimal](./readdecimal/)() | NO IMPLEMENTADO. |
| virtual [ReadDouble](./readdouble/)() | Lee 8 bytes del flujo de entrada y los devuelve como un valor de punto flotante de doble precisión. |
| virtual [ReadInt16](./readint16/)() | Lee 2 bytes del flujo de entrada y los devuelve como un valor entero de 16 bits. |
| virtual [ReadInt32](./readint32/)() | Lee 4 bytes del flujo de entrada y los devuelve como un valor entero de 32 bits. |
| virtual [ReadInt64](./readint64/)() | Lee 8 bytes del flujo de entrada y los devuelve como un valor entero de 64 bits. |
| virtual [ReadSByte](./readsbyte/)() | Lee un solo byte del flujo de entrada y lo devuelve como un valor entero con signo de 8 bits. |
| virtual [ReadSingle](./readsingle/)() | Lee 4 bytes del flujo de entrada y los devuelve como un valor de punto flotante de precisión simple. |
| virtual [ReadString](./readstring/)() | Lee una cadena del flujo actual. La cadena está precedida por la longitud, codificada como un entero de siete bits a la vez. |
| virtual [ReadUInt16](./readuint16/)() | Lee 2 bytes del flujo de entrada y los devuelve como un valor entero sin signo de 16 bits. |
| virtual [ReadUInt32](./readuint32/)() | Lee 4 bytes del flujo de entrada y los devuelve como un valor entero sin signo de 32 bits. |
| virtual [ReadUInt64](./readuint64/)() | Lee 8 bytes del flujo de entrada y los devuelve como un valor entero sin signo de 64 bits. |
| virtual [~BinaryReader](./~binaryreader/)() | Destructor. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
