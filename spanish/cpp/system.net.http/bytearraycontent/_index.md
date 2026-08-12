---
title: "System::Net::Http::ByteArrayContent clase"
linktitle: "ByteArrayContent"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::ByteArrayContent class. Representa el contenido HTTP como una matriz de bytes. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++."
type: docs
weight: 100
url: /es/cpp/system.net.http/bytearraycontent/
---
## ByteArrayContent class


Representa el contenido HTTP como una matriz de bytes. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/) . Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ByteArrayContent : public System::Net::Http::HttpContent
```

## Métodos

| Método | Descripción |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/)(System::ArrayPtr\<uint8_t\>) | Información RTTI. |
| [ByteArrayContent](./bytearraycontent/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) | Construye una nueva instancia. |
| [TryComputeLength](./trycomputelength/)(int64_t\&) override | Intenta calcular la longitud de la matriz de bytes. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [DefaultStringEncoding](../httpcontent/defaultstringencoding/) | La codificación predeterminada. |
| static [MaxBufferSize](../httpcontent/maxbuffersize/) | El número máximo de bytes. |
## Ver también

* Class [HttpContent](../httpcontent/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
