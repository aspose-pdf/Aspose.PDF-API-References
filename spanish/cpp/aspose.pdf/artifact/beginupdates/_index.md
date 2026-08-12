---
title: "Aspose::Pdf::Artifact::BeginUpdates método"
linktitle: "BeginUpdates"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Artifact::BeginUpdates método. Inicia actualizaciones diferidas. Use esta función si necesita realizar varios cambios en el mismo artefacto para mejorar el rendimiento. Normalmente los operadores del artefacto se cambian cada vez que se modifica una propiedad del artefacto. Esto provoca el cambio del contenido de la página cada vez que el artefacto se modifica. Para evitar este efecto, coloque todas las actualizaciones del artefacto entre llamadas a BeginUpdates/SaveUpdates. Esto permite cambiar el contenido de la página solo una vez en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf/artifact/beginupdates/
---
## Artifact::BeginUpdates method


Inicie actualizaciones retrasadas. Use esta función si necesita realizar varios cambios al mismo artefacto para mejorar el rendimiento. Normalmente los operadores del artefacto se modifican cada vez que se cambia una propiedad del artefacto. Esto provoca la modificación del contenido de la página cada vez que el artefacto se cambia. Para evitar este efecto, coloque todas las actualizaciones del artefacto entre las llamadas StartUpdates/SaveUpdates. Esto permite cambiar el contenido de la página solo una vez.

```cpp
void Aspose::Pdf::Artifact::BeginUpdates()
```

## Ver también

* Class [Artifact](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
