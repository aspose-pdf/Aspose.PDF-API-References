---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter-Methode. Konvertieren Sie die FDF-Datei in XML
type: docs
weight: 120
url: /de/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml-Methode

Konvertieren Sie die FDF-Datei in XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceFdf | Stream | Stream, der das FDF enthält, das konvertiert werden soll. |
| destXml | Stream | Quelle, in der das Ergebnis-XML platziert wird. |

## Beispiele

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### Siehe auch

* Klasse [FormDataConverter](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)