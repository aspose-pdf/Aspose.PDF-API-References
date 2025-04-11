---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Id. Representa la estructura del identificador de archivo
type: docs
weight: 5850
url: /es/net/aspose.pdf/id/
---
## Clase Id

Representa la estructura del identificador de archivo.

```csharp
public class Id
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Modificado](../../aspose.pdf/id/modified/) { get; } | Cambiando el identificador basado en el contenido del documento en el momento en que fue actualizado por última vez. |
| [Original](../../aspose.pdf/id/original/) { get; } | Identificador permanente basado en el contenido del documento en el momento en que fue creado originalmente. |

## Ejemplos

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)