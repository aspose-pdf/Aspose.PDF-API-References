---
title: "PdfXmpMetadata"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe para manipulação de metadados XMP."
type: docs
weight: 380
url: /pt/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

Classe para manipulação de metadados XMP.

O tipo PdfXmpMetadata expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfXmpMetadata() | Construtor para PdfXmpMetadata. |
| PdfXmpMetadata(document) | Inicializa uma nova instância da classe PdfXmpMetadata |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| chaves | Obtém chaves do dicionário. |
| valores | Obtém a coleção de valores no dicionário. |
| is_fixed_size | Retorna true se a coleção tem tamanho fixo. |
| is_synchronized | Retorna true se a coleção está sincronizada. |
| sync_root | Obtém o objeto de sincronização da coleção. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(src_file) | Vincula o documento PDF para edição. |
| bind_pdf(src_stream) | Vincula o documento PDF para edição. |
| bind_pdf(src_doc) | Vincula o documento PDF para edição. |
| save(dest_file) | Salva o documento PDF no arquivo especificado. |
| save(dest_stream) | Salva o documento PDF no fluxo especificado. |
| add(key, value) | Adiciona valor ao metadata XMP. |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | Adiciona campo de extensão ao metadata. |
| add(key, value) | Adiciona novo elemento ao objeto dicionário. |
| add(key, value) | Adiciona campo de extensão ao metadata. |
| remove(key) | Remove elemento com a chave especificada. |
| remove(key) | Remove chave do dicionário. |
| contains(key) | Verifica se o dicionário contém a chave especificada. |
| contains(property) | Verifica se o dicionário contém a propriedade especificada. |
| get_xmp_metadata() | Obtém o XmpMetadata do PDF de entrada em formato XML. |
| get_xmp_metadata(name) | Obtenha uma parte do XmpMetadata do PDF de entrada de acordo com um nome de meta. |
| close() | Libera quaisquer recursos associados à fachada atual. |
| register_namespace_uri(prefix, namespace_uri) | Registra o URI do namespace. |
| get_namespace_uri_by_prefix(prefix) | Obtém o URI do namespace pelo prefixo. |
| get_prefix_by_namespace_uri(namespace_uri) | Obtém o prefixo pelo URI do namespace. |
| contains_key(key) | Determina se este dicionário contém a chave especificada. |
| try_get_value(key, value) | Tenta encontrar a chave no dicionário e recupera o valor se encontrado. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

