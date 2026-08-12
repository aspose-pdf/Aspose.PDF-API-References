---
title: "Aspose::Pdf::SignaturesCompromiseDetector::Check método"
linktitle: "Check"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::SignaturesCompromiseDetector::Check método. Verifica las firmas digitales del documento en busca de compromisos en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector::Check method


Verifica si las firmas digitales del documento están comprometidas.

```cpp
bool Aspose::Pdf::SignaturesCompromiseDetector::Check(System::SharedPtr<Signatures::CompromiseCheckResult> &compromiseCheckResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| compromiseCheckResult | System::SharedPtr\<Signatures::CompromiseCheckResult\>\& | El resultado de la verificación del documento. |

### ReturnValue

True, si no se detecta el compromiso de las firmas.
## Observaciones



El uso de este método para un documento en el que no hay firmas digitales devolverá **True**.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* Class [SignaturesCompromiseDetector](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
