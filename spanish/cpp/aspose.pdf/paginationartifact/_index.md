---
title: "Aspose::Pdf::PaginationArtifact class"
linktitle: "PaginationArtifact"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PaginationArtifact class. Representa una clase base abstracta para artefactos de paginación en un documento en C++."
type: docs
weight: 14500
url: /es/cpp/aspose.pdf/paginationartifact/
---
## PaginationArtifact class


Representa una clase base abstracta para artefactos de paginación en un documento.

```cpp
class PaginationArtifact : public Aspose::Pdf::Artifact
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_EndPage](./get_endpage/)() const | Obtiene el número de página final del artefacto. El valor debe ser mayor o igual que 0. Si se establece un valor menor que 0, se ajustará a 0. El valor predeterminado de 0 significa que no hay límites de página finales. |
| [get_StartPage](./get_startpage/)() const | Obtiene el número de página inicial del artefacto. El valor debe ser mayor o igual que 1. Si se establece un valor menor que 1, se ajustará a 1. |
| [get_Subset](./get_subset/)() const | Obtiene el subconjunto de páginas al que se aplica el artefacto (p. ej., todas las páginas, páginas pares, páginas impares). |
| [set_EndPage](./set_endpage/)(int32_t) | Establece el número de página final del artefacto. El valor debe ser mayor o igual que 0. Si se establece un valor menor que 0, se ajustará a 0. El valor predeterminado de 0 significa que no hay límites de página finales. |
| [set_StartPage](./set_startpage/)(int32_t) | Establece el número de página inicial del artefacto. El valor debe ser mayor o igual que 1. Si se establece un valor menor que 1, se ajustará a 1. |
| [set_Subset](./set_subset/)(Aspose::Pdf::Subset) | Establece el subconjunto de páginas al que se aplica el artefacto (p. ej., todas las páginas, páginas pares, páginas impares). |
## Ver también

* Class [Artifact](../artifact/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
