---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfPageEditor. Enregistre le document modifié dans un fichier
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
| outputFile | String | Chemin vers le fichier où le document sera enregistré. |

## Exemples

L'exemple suivant montre comment enregistrer un document PDF modifié

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Voir aussi

* classe [PdfPageEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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

L'exemple suivant montre comment enregistrer un document PDF modifié dans un flux.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Voir aussi

* classe [PdfPageEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)