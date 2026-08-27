---
title: "FormDataConverter.ConvertFdfToXml"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "FormDataConverter méthode. Convertit le fichier FDF en XML"
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml method

Convertir le fichier FDF en XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceFdf | Stream | Flux contenant le FDF à convertir. |
| destXml | Stream | Source où le XML résultant sera placé. |

## Exemples

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### Voir aussi

* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


