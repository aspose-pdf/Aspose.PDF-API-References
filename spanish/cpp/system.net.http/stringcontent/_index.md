---
title: "System::Net::Http::StringContent clase"
linktitle: "StringContent"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::Http::StringContent. Representa contenido HTTP como una cadena. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 1100
url: /es/cpp/system.net.http/stringcontent/
---
## StringContent class


Representa contenido HTTP como una cadena. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class StringContent : public System::Net::Http::ByteArrayContent
```

## Métodos

| Método | Descripción |
| --- | --- |
| [StringContent](./stringcontent/)(String) | Información RTTI. |
| [StringContent](./stringcontent/)(String, System::SharedPtr\<Text::Encoding\>) | Construye una nueva instancia. |
| [StringContent](./stringcontent/)(String, System::SharedPtr\<Text::Encoding\>, String) | Construye una nueva instancia. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [DefaultStringEncoding](../httpcontent/defaultstringencoding/) | La codificación predeterminada. |
| static [MaxBufferSize](../httpcontent/maxbuffersize/) | El número máximo de bytes. |
## Ver también

* Class [ByteArrayContent](../bytearraycontent/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
