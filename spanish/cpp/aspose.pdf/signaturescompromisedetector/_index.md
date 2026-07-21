---
title: "Clase Aspose::Pdf::SignaturesCompromiseDetector"
linktitle: "SignaturesCompromiseDetector"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::SignaturesCompromiseDetector. Representa una clase para verificar firmas comprometidas del documento en C++."
type: docs
weight: 17300
url: /es/cpp/aspose.pdf/signaturescompromisedetector/
---
## SignaturesCompromiseDetector class


Representa una clase para comprobar firmas comprometedoras del documento.

```cpp
class SignaturesCompromiseDetector : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Check](./check/)(System::SharedPtr\<Signatures::CompromiseCheckResult\>\&) | Verifica si las firmas digitales del documento están comprometidas. |
| [SignaturesCompromiseDetector](./signaturescompromisedetector/)(const System::SharedPtr\<Document\>\&) | Crea una instancia de la clase [SignaturesCompromiseDetector](./). |
## Observaciones


El detector verifica solo los métodos conocidos para comprometer firmas. La verificación no puede ofrecer una garantía del 100% de la ausencia de compromisos de firmas y puede producir un resultado falso negativo para métodos de compromiso nuevos y desconocidos diferentes de los que se están probando.
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
