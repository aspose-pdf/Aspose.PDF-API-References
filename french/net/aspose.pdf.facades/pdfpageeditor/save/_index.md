---
title: "PdfPageEditor.Save"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfPageEditor. Enregistre le document modifié dans un fichier"
type: docs
weight: 180
url: /fr/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Enregistre le document modifié dans un fichier.

```csharp
public override void Save(string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Chemin du fichier où le document sera enregistré. |

## Exemples

L'exemple suivant montre comment enregistrer le document PDF modifié

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Voir aussi

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Enregistre le document modifié dans un flux.

```csharp
public override void Save(Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Flux où le document PDF modifié sera enregistré. |

## Exemples

L'exemple suivant montre comment enregistrer le document PDF modifié dans un flux.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Voir aussi

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


