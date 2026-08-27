---
title: "PdfFileSanitization"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa a API de sanitização e recuperação.<br/>            Use-a se você não conseguir criar/abrir documentos de outra forma."
type: docs
weight: 290
url: /pt/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

Representa a API de sanitização e recuperação.<br/>            Use-a se você não conseguir criar/abrir documentos de outra forma.

O tipo PdfFileSanitization expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfFileSanitization() | Inicializa uma nova instância da classe PdfFileSanitization |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| log | Depois que o arquivo foi salvo, você pode verificar o que foi feito com o arquivo. |
| use_trim_top | Permite remover dados antes dos dados pdf. |
| use_trim_bottom | Permite remover dados após os dados pdf |
| use_rebuild_xref_and_trailer | Permite gerar novo xref e trailer para o documento. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(input_file) | Associa um arquivo Pdf para sanitização. |
| bind_pdf(input_stream) | Associa um fluxo Pdf para sanitização. |
| bind_pdf(src_doc) | Inicializa a fachada. |
| save(output_file) | Salva o PDF resultante em um arquivo. |
| save(output_stream) | Salva o PDF resultante em um fluxo. |
| close() | Fecha a fachada. |
| recover() | Recupera o documento.<br/>            Use propriedades para personalizar. |
| trim_top() | Remove dados antes de %PDF. |
| trim_bottom() | Remove dados após o último %%EOF. |
| rebuild_xref_and_trailer() | Remove o xref antigo com trailer e cria um novo xref com trailer. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

