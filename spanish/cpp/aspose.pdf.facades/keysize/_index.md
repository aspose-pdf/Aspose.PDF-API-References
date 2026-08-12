---
title: "Aspose::Pdf::Facades::KeySize enum"
linktitle: "KeySize"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::KeySize enum. Define diferentes tamaños de clave que pueden usarse para cifrar documentos pdf en C++."
type: docs
weight: 4800
url: /es/cpp/aspose.pdf.facades/keysize/
---
## KeySize enum


Define diferentes tamaños de clave que pueden usarse para encriptar documentos PDF.

```cpp
enum class KeySize
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| x40 | 0 | Clave de 40 bits. Este tamaño de clave se usa con el algoritmo RC4 y proporciona un bajo nivel de seguridad. Sin embargo, las versiones antiguas de documentos pdf solo pueden cifrarse con dichas claves (v. 1.3 y anteriores); |
| x128 | 1 | Clave de 128 bits. Tanto los algoritmos RC4 como AES pueden usar este tamaño de clave. |
| x256 | 2 | Clave de 256 bits. Este tamaño de clave solo puede usarse con AES y es reconocido por las últimas versiones de Adobe Reader (a partir de la v.9). |

## Ver también

* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
