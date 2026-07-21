---
title: "System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength método"
linktitle: "GetTransferCodingLength"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength método. Convierte una cadena pasada desde el índice especificado a una instancia de la clase TransferCodingHeaderValue en C++."
type: docs
weight: 700
url: /es/cpp/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength method


Convierte una cadena pasada desde el índice especificado a una instancia de la clase [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | String | Una cadena para analizar. |
| startIndex | int32_t | Una posición inicial para el análisis. |
| parsedValue | const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\& | Una instancia donde se asignará un objeto analizado. |
| transferCodingCreator | System::SharedPtr\<TransferCodingHeaderValue\>\& | El delegado que se usa para crear instancias de la clase [TransferCodingHeaderValue](../). |

### ReturnValue

Devuelve la longitud de una subcadena analizada, de lo contrario 0.

## Ver también

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TransferCodingHeaderValue](../)
* Class [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
