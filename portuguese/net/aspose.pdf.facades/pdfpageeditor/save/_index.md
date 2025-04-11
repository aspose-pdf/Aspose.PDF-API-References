---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: Método PdfPageEditor. Salva o documento alterado em um arquivo
type: docs
weight: 180
url: /pt/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Salva o documento alterado em um arquivo.

```csharp
public override void Save(string outputFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFile | String | Caminho para o arquivo onde o documento será salvo. |

## Exemplos

O seguinte exemplo demonstra como salvar um documento PDF alterado

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Veja Também

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Salva o documento alterado em um stream.

```csharp
public override void Save(Stream outputStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputStream | Stream | Stream onde o documento PDF alterado será salvo. |

## Exemplos

O seguinte exemplo demonstra como salvar um documento PDF alterado em um stream.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Veja Também

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)