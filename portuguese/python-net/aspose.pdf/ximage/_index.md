---
title: "XImage"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe que representa o X-Object de imagem."
type: docs
weight: 1680
url: /pt/python-net/aspose.pdf/ximage/
---

## XImage class

Classe que representa o X-Object de imagem.

O tipo XImage expõe os seguintes membros:
## Propriedades
| Nome | Descrição |
| :- | :- |
| contains_transparency | Se a imagem contém transparência, retorna true; caso contrário, false. |
| grayscaled | Obtém a versão em tons de cinza da imagem. |
| filter_type | Obtém o tipo de filtro da imagem. |
| largura | Obtém a largura da imagem. |
| altura | Obtém a altura da imagem. |
| nome | Obtém ou define o nome da imagem. Observe que, se você alterar o nome da imagem que tem referências no conteúdo da página, o documento pode ficar incorreto. Use o método XImage.Rename neste caso. |
| metadata | Metadados da imagem. |
## Métodos
| Nome | Descrição |
| :- | :- |
| save(stream) | Salva os dados da imagem em um stream como imagem JPEG. |
| save(stream, format) | Salva a imagem em um stream com o formato solicitado. |
| save(stream, resolution) | Salva os dados da imagem em um stream como imagem JPEG com resolução especificada. |
| save(stream, format, resolution) | Salva a imagem em um stream com o formato solicitado e resolução especificada. |
| rename(name) | Renomeia a imagem e substitui todas as referências à imagem pelo novo nome |
| get_color_type() | Retorna o tipo de cor da imagem. |
| detect_color_type(bmp) | Retorna o tipo de cor da imagem. |
| is_the_same_object(image) | Retorna verdadeiro se ambas as imagens referenciam o mesmo objeto. |
| get_name_in_collection() | Retorna o nome da imagem na coleção de inteiros. |
| to_stream() | Retorna o fluxo de imagem original. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

