---
title: "Aspose::Pdf::BatesNArtifact clase"
linktitle: "BatesNArtifact"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::BatesNArtifact clase. La clase describe el artefacto de numeración Bates en C++."
type: docs
weight: 1100
url: /es/cpp/aspose.pdf/batesnartifact/
---
## BatesNArtifact class


Clase que describe el artefacto de numeración Bates.

```cpp
class BatesNArtifact : public Aspose::Pdf::PaginationArtifact
```

## Métodos

| Método | Descripción |
| --- | --- |
| [BatesNArtifact](./batesnartifact/)() | Inicializa una nueva instancia de la clase [BatesNArtifact](./). Este constructor es interno y crea una instancia de artefacto de encabezado con valores predeterminados. |
| [get_NumberOfDigits](./get_numberofdigits/)() const | Obtiene el número de dígitos para la numeración Bates. El valor debe estar entre 3 y 15 inclusive. Si se establece un valor menor que 3, se ajustará a 3. Si se establece un valor mayor que 15, se ajustará a 15. El valor predeterminado es 6. |
| [get_Prefix](./get_prefix/)() const | Obtiene el prefijo que se añadirá al número Bates. |
| [get_StartNumber](./get_startnumber/)() const | Obtiene el número inicial para la numeración Bates. El valor debe ser mayor o igual a 1. Si se establece un valor menor que 1, se ajustará a 1. |
| [get_Suffix](./get_suffix/)() const | Obtiene el sufijo que se añadirá al número Bates. |
| [set_NumberOfDigits](./set_numberofdigits/)(int32_t) | Establece el número de dígitos para la numeración Bates. El valor debe estar entre 3 y 15 inclusive. Si se establece un valor menor que 3, se ajustará a 3. Si se establece un valor mayor que 15, se ajustará a 15. El valor predeterminado es 6. |
| [set_Prefix](./set_prefix/)(const System::String\&) | Establece el prefijo que se añadirá al número Bates. |
| [set_StartNumber](./set_startnumber/)(int32_t) | Establece el número inicial para la numeración Bates. El valor debe ser mayor o igual a 1. Si se establece un valor menor que 1, se ajustará a 1. |
| [set_Suffix](./set_suffix/)(const System::String\&) | Establece el sufijo que se añadirá al número Bates. |
## Ver también

* Class [PaginationArtifact](../paginationartifact/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
