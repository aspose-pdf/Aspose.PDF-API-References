---
title: "System::Globalization::TextInfo class"
linktitle: "TextInfo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Globalization::TextInfo class. Define propiedades de texto específicas de la configuración regional. Las operaciones de establecimiento solo están habilitadas en objetos que no son de solo lectura. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 2800
url: /es/cpp/system.globalization/textinfo/
---
## TextInfo class


Define propiedades de texto específicas de la configuración regional. Las operaciones de establecimiento solo están habilitadas en objetos que no son de solo lectura. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class TextInfo : public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Clone](./clone/)() override | Información RTTI. |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| virtual [get_ANSICodePage](./get_ansicodepage/)() const | Obtiene la página de códigos ANSI. |
| [get_CultureName](./get_culturename/)() const | Obtiene el nombre de la cultura. |
| virtual [get_EBCDICCodePage](./get_ebcdiccodepage/)() const | Obtiene la página de códigos EBCDIC. |
| [get_IsReadOnly](./get_isreadonly/)() const | Comprueba si el formato es de solo lectura. |
| [get_IsRightToLeft](./get_isrighttoleft/)() const | Comprueba si el texto se escribe de izquierda a derecha. |
| [get_LCID](./get_lcid/)() const | Obtiene el ID de configuración regional. |
| virtual [get_ListSeparator](./get_listseparator/)() const | Obtiene el separador de lista. |
| virtual [get_MacCodePage](./get_maccodepage/)() const | Obtiene la página de códigos Macintosh. |
| virtual [get_OEMCodePage](./get_oemcodepage/)() const | Obtiene la página de códigos OEM. |
| [GetHashCode](./gethashcode/)() const override | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [operator=](./operator=/)(const TextInfo\&) |  |
| static [ReadOnly](./readonly/)(const TextInfoPtr\&) | Obtiene una versión de solo lectura de la cultura. |
| virtual [set_ListSeparator](./set_listseparator/)(String) | Establece el separador de lista. |
| [TextInfo](./textinfo/)(const TextInfo\&) | Información RTTI. |
| virtual [ToLower](./tolower/)(char_t) const | Convierte el carácter a minúsculas. |
| virtual [ToLower](./tolower/)(String) const | Convierte la cadena a minúsculas. |
| [ToString](./tostring/)() const override | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| [ToTitleCase](./totitlecase/)(String) const | Convierte la cadena a mayúsculas de título (excepto los acrónimos que ya están en mayúsculas). |
| virtual [ToUpper](./toupper/)(char_t) const | Convierte el carácter a mayúsculas. |
| virtual [ToUpper](./toupper/)(String) const | Convierte la cadena a mayúsculas. |
## Ver también

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
