---
title: "Form.ImportXml"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf."
type: docs
weight: 310
url: /fr/net/aspose.pdf.facades/form/importxml/
---
## ImportXml(Stream) {#importxml}

Importe le contenu des champs du fichier xml et les place dans le nouveau pdf.

```csharp
public void ImportXml(Stream inputXmlStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputXmlStream | Stream | Flux à partir duquel le XML à importer est lu. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
FileStream fs = new FileStream(TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
form.ImportXml(fs);
form.Save();
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportXml(Stream, bool) {#importxml_1}

Importe le contenu des champs du fichier xml et les place dans le nouveau pdf.

```csharp
public void ImportXml(Stream inputXmlStream, bool IgnoreFormTemplateChanges)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputXmlStream | Stream | Le flux xml d'entrée. |
| IgnoreFormTemplateChanges | Boolean | Si ce paramètre est vrai, alors toutes les modifications du modèle de formulaire XFA ne seront pas enregistrées. |

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


