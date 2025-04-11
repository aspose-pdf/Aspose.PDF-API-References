---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: Método FormDataConverter. Converter arquivo FDF em XML
type: docs
weight: 120
url: /pt/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## Método FormDataConverter.ConvertFdfToXml

Converter arquivo FDF em XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceFdf | Stream | Stream que contém o FDF a ser convertido. |
| destXml | Stream | Fonte onde o XML resultante será colocado. |

## Exemplos

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### Veja Também

* classe [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)