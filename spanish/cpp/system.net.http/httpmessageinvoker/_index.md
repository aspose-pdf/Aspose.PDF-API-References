---
title: "System::Net::Http::HttpMessageInvoker class"
linktitle: "HttpMessageInvoker"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::HttpMessageInvoker class. Permite a las aplicaciones llamar al método Send en una cadena de controladores HTTP. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++."
type: docs
weight: 600
url: /es/cpp/system.net.http/httpmessageinvoker/
---
## HttpMessageInvoker class


Permite a las aplicaciones llamar al método Send en una cadena de controladores HTTP. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpMessageInvoker : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Dispose](./dispose/)() override | Elimina la instancia actual. Este método también elimina el controlador si es necesario. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>) | Información RTTI. |
| [HttpMessageInvoker](./httpmessageinvoker/)(System::SharedPtr\<HttpMessageHandler\>, bool) | Construye una nueva instancia. |
| virtual [Send](./send/)(System::SharedPtr\<HttpRequestMessage\>) | Envía la solicitud especificada. |
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
