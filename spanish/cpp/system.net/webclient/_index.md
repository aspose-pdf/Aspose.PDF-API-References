---
title: "Clase System::Net::WebClient"
linktitle: "WebClient"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Net::WebClient. WebClient proporciona métodos comunes para enviar y recibir datos. Los objetos de esta clase solo deben asignarse mediante la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento en C++."
type: docs
weight: 3500
url: /es/cpp/system.net/webclient/
---
## WebClient class


[WebClient](./) provides common methods for sending and receiving data. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebClient : public System::ComponentModel::Component
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DownloadData](./downloaddata/)(const String\&) const | Descarga el recurso especificado como una matriz de bytes. |
| [DownloadData](./downloaddata/)(const SharedPtr\<Uri\>\&) const | Descarga el recurso especificado como una matriz de bytes. |
| [DownloadString](./downloadstring/)(const String\&) const | Descarga el recurso especificado como una cadena. |
| [DownloadString](./downloadstring/)(const SharedPtr\<Uri\>\&) const | Descarga el recurso especificado como una cadena. |
| [get_Encoding](./get_encoding/)() const | Obtiene la codificación utilizada para descargar o subir cadenas. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<Text::Encoding\>\&) | Establece la codificación utilizada para descargar o subir cadenas. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | NO IMPLEMENTADO. |
| [WebClient](./webclient/)() | Información RTTI. |
| [~WebClient](./~webclient/)() | Destruye la instancia actual. |
## Ver también

* Class [Component](../../system.componentmodel/component/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
