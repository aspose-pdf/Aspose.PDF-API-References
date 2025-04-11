---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: Método FormDataConverter. Convertir archivo FDF en XML
type: docs
weight: 120
url: /es/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## Método FormDataConverter.ConvertFdfToXml

Convertir archivo FDF en XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceFdf | Stream | Flujo que contiene el FDF a convertir. |
| destXml | Stream | Fuente donde se colocará el XML resultante. |

## Ejemplos

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### Ver También

* clase [FormDataConverter](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)