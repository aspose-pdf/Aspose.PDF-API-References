---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter-metod. Konvertera FDF-fil till XML
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml metod

Konvertera FDF-fil till XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFdf | Stream | Stream som innehåller FDF att konvertera. |
| destXml | Stream | Källa där resultat-XML kommer att placeras. |

## Exempel

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### Se Även

* klass [FormDataConverter](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)