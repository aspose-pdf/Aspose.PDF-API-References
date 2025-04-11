---
title: Metered.SetMeteredKey
second_title: Aspose.PDF for .NET API Reference
description: Método medido. Establece la clave pública y privada medida. Si compras una licencia medida, al iniciar la aplicación, esta API debe ser llamada, normalmente, esto es suficiente. Sin embargo, si siempre falla al cargar los datos de consumo y excede las 24 horas, la licencia se establecerá en estado de evaluación, para evitar tal caso, debes verificar regularmente el estado de la licencia, si está en estado de evaluación, llama a esta API nuevamente.
type: docs
weight: 30
url: /es/net/aspose.pdf/metered/setmeteredkey/
---
## Método Metered.SetMeteredKey

Establece la clave pública y privada medida. Si compras una licencia medida, al iniciar la aplicación, esta API debe ser llamada, normalmente, esto es suficiente. Sin embargo, si siempre falla al cargar los datos de consumo y excede las 24 horas, la licencia se establecerá en estado de evaluación, para evitar tal caso, debes verificar regularmente el estado de la licencia, si está en estado de evaluación, llama a esta API nuevamente.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicKey | String | clave pública |
| privateKey | String | clave privada |

### Ver También

* clase [Metered](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)