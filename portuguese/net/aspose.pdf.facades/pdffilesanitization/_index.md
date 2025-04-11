---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileSanitization. Representa a API de sanitização e recuperação. Use-a se você não conseguir criar/abrir documentos de outra forma
type: docs
weight: 4540
url: /pt/net/aspose.pdf.facades/pdffilesanitization/
---
## Classe PdfFileSanitization

Representa a API de sanitização e recuperação. Use-a se você não conseguir criar/abrir documentos de outra forma.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | Após o arquivo ter sido salvo, você pode verificar o que foi feito com o arquivo. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | Permite gerar um novo xref e trailer para o documento. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | Permite remover dados após os dados do pdf. |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | Permite remover dados antes dos dados do pdf. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Inicializa a fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | Vincula um fluxo Pdf para Sanitizar. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Vincula um arquivo Pdf para Sanitizar. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Fecha a fachada. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Descarte a fachada. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | Remove o xref antigo com trailer e cria um novo xref com trailer. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | Recupera o documento. Use propriedades para personalizar. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | Salva o PDF resultante no fluxo. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | Salva o PDF resultante no arquivo. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | Remove dados após o último %%EOF. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | Remove dados antes de %PDF. |

### Veja Também

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)