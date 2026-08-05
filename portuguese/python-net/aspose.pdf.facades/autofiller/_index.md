---
title: "AutoFiller"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma classe para receber dados de um banco de dados ou outra fonte de dados, preenchê‑los nos campos projetados do PDF modelo e, ao final, gerar um novo arquivo PDF ou stream.<br/>             Possui dois modos de entrada de arquivo modelo: entrada como stream ou como arquivo PDF.<br/>             Possui quatro tipos de modos de saída: um stream mesclado, um arquivo mesclado, vários streams pequenos, vários arquivos pequenos.<br/>             Pode receber dados literais contidos em um System.Data.DataTable."
type: docs
weight: 20
url: /pt/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

Representa uma classe para receber dados de um banco de dados ou outra fonte de dados, preenchê‑los nos campos projetados do PDF modelo e, ao final, gerar um novo arquivo PDF ou stream.<br/>             Possui dois modos de entrada de arquivo modelo: entrada como stream ou como arquivo PDF.<br/>             Possui quatro tipos de modos de saída: um stream mesclado, um arquivo mesclado, vários streams pequenos, vários arquivos pequenos.<br/>             Pode receber dados literais contidos em um System.Data.DataTable.

O tipo AutoFiller expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| AutoFiller() | Inicializa uma nova instância da classe AutoFiller |
## Propriedades
| Nome | Descrição |
| :- | :- |
| output_stream | Obtém ou define o OutputStream. Um dos quatro modos de saída. Seu caso de uso clássico é Response.OutputStream.<br/>            Consulte a demonstração online. |
| output_streams | Obtém ou define os vários Output Streams. Um dos quatro modos de saída. |
| input_stream | Obtém ou define o fluxo de modelo de entrada. Um dos dois modos de entrada. |
| input_file_name | Obtém ou define o arquivo de modelo de entrada. Um dos dois modos de entrada. |
| output_file_name | Obtém ou define o único grande arquivo de saída mesclado. Um dos quatro modos de saída. |
| generating_path | Obtém ou define o Caminho de Geração dos pequenos arquivos pdf se muitos pequenos arquivos pdf forem gerados. Funciona com outra propriedade [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName.<br/>            Um dos quatro modos de saída. |
| basic_file_name | Obtém ou define o nome de arquivo básico se muitos arquivos pequenos forem gerados. O arquivo gerado será como "BasicFileName0","BasicFileName1",...<br/>            Funciona com outra propriedade [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath. |
## Métodos
| Nome | Descrição |
| :- | :- |
| save() | Salva todos os PDFs. |
| save(dest_file) | Salva todos os PDFs. |
| save(dest_stream) | Salva todos os PDFs. |
| bind_pdf(src_file) | Associa um arquivo PDF. |
| bind_pdf(src_stream) | Associa um arquivo PDF. |
| bind_pdf(src_doc) | Associa um documento PDF. |
| close() | Fecha o objeto e os fluxos de saída. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

