---
title: "Método Aspose::Pdf::Metered::SetMeteredKey"
linktitle: "SetMeteredKey"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Metered::SetMeteredKey method. Establece la clave pública y privada de metered. Si compras una licencia metered, al iniciar la aplicación, esta API debe ser llamada; normalmente, eso es suficiente. Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se cambiará a estado de evaluación; para evitar este caso, deberías comprobar regularmente el estado de la licencia y, si está en estado de evaluación, llamar a esta API nuevamente en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf/metered/setmeteredkey/
---
## Metered::SetMeteredKey method


Establece la clave pública y privada de metered. Si compra una licencia metered, al iniciar la aplicación, debe llamarse a esta API; normalmente, eso es suficiente. Sin embargo, si siempre falla la carga de los datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar este caso, debe comprobar regularmente el estado de la licencia y, si está en estado de evaluación, volver a llamar a esta API.

```cpp
void Aspose::Pdf::Metered::SetMeteredKey(const System::String &publicKey, const System::String &privateKey)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKey | const System::String\& | clave pública |
| privateKey | const System::String\& | clave privada |

## Ver también

* Class [String](../../../system/string/)
* Class [Metered](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
