---
title: "Clase System::Xml::XmlCharacterData"
linktitle: "XmlCharacterData"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Xml::XmlCharacterData. Proporciona métodos de manipulación de texto que son utilizados por varias clases en C++."
type: docs
weight: 900
url: /es/cpp/system.xml/xmlcharacterdata/
---
## XmlCharacterData class


Proporciona métodos de manipulación de texto que son usados por varias clases.

```cpp
class XmlCharacterData : public System::Xml::XmlLinkedNode
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [AppendData](./appenddata/)(String) | Añade la cadena especificada al final de los datos de caracteres del nodo. |
| virtual [DeleteData](./deletedata/)(int32_t, int32_t) | Elimina un rango de caracteres del nodo. |
| virtual [get_Data](./get_data/)() | Devuelve los datos del nodo. |
| [get_InnerText](./get_innertext/)() override | Devuelve los valores concatenados del nodo y de todos sus hijos. |
| virtual [get_Length](./get_length/)() | Devuelve la longitud de los datos, en caracteres. |
| [get_Value](./get_value/)() override | Devuelve el valor del nodo. |
| virtual [InsertData](./insertdata/)(int32_t, String) | Inserta la cadena especificada en la posición de carácter especificada. |
| virtual [ReplaceData](./replacedata/)(int32_t, int32_t, String) | Reemplaza el número especificado de caracteres a partir del desplazamiento especificado con la cadena especificada. |
| virtual [set_Data](./set_data/)(String) | Establece los datos del nodo. |
| [set_InnerText](./set_innertext/)(String) override | Establece los valores concatenados del nodo y de todos sus hijos. |
| [set_Value](./set_value/)(String) override | Establece el valor del nodo. |
| virtual [Substring](./substring/)(int32_t, int32_t) | Recupera una subcadena de la cadena completa del rango especificado. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [Ptr](./ptr/) | Un alias para un puntero compartido a una instancia de esta clase. |
## Ver también

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
