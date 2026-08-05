---
title: "BackgroundArtifact"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe descreve artefato de fundo. Este artefato permite definir o fundo da página."
type: docs
weight: 50
url: /pt/python-net/aspose.pdf/backgroundartifact/
---

## BackgroundArtifact class

Classe descreve artefato de fundo. Este artefato permite definir o fundo da página.

O tipo BackgroundArtifact expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| BackgroundArtifact() | Inicializa o objeto BackgroundArtifact. |
## Propriedades
| Nome | Descrição |
| :- | :- |
| custom_type | Obtém o nome do tipo de artefato. Pode ser usado se o tipo de artefato não for padrão. |
| custom_subtype | Obtém o nome do subtipo de artefato. Pode ser usado se o subtipo de artefato não for um subtipo padrão. |
| type | Obtém o tipo de artefato. |
| subtype | Obtém o subtipo de artefato. Se o artefato tiver um subtipo não padrão, o nome do subtipo pode ser lido via CustomSubtype. |
| conteúdo | Obtém a coleção de operadores internos do artefato. |
| formulário | Obtém o XForm do artefato (se o XForm for usado). |
| rectangle | Obtém o retângulo do artefato. |
| position | Obtém ou define a posição do artefato.<br/>            Se esta propriedade for especificada, as margens e alinhamentos são ignorados. |
| right_margin | Margem direita do artefato. <br/>            Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| left_margin | Margem esquerda do artefato. <br/>            Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| top_margin | Margem superior do artefato. <br/>            Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| bottom_margin | Margem inferior do artefato. <br/>            Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| artifact_horizontal_alignment | Alinhamento horizontal do artefato. <br/>            Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| artifact_vertical_alignment | Alinhamento vertical do artefato. <br/>            Se a posição for especificada explicitamente (na propriedade Position) este valor será ignorado. |
| rotation | Obtém ou define o ângulo de rotação do artefato. |
| text | Obtém o texto do artefato. |
| image | Obtém a imagem do artefato (se presente). |
| opacidade | Obtém ou define a opacidade do artefato. Valores possíveis estão no intervalo 0..1. |
| linhas | Linhas do artefato de texto multilinha. |
| text_state | Estado do texto para o texto do artefato. |
| is_background | Se verdadeiro, o artefato é colocado atrás do conteúdo da página. |
| background_color | Obtém ou define a cor de fundo do artefato de fundo |
| background_image | Obtém ou define a imagem de fundo do artefato de fundo |
## Métodos
| Nome | Descrição |
| :- | :- |
| set_image(image_stream) | Define a imagem do artefato. |
| set_image(image_name) | Define a imagem do artefato. |
| set_text(formatted_text) | Define o texto do artefato. |
| set_text_and_state(text, text_state) | Define o texto e as propriedades de texto do artefato. |
| set_lines_and_state(text, text_state) | Define o texto e as propriedades de texto do artefato. Permite especificar várias linhas. |
| set_pdf_page(page) | Define a página PDF que é colocada na página do documento como artefato. |
| get_value(name) | Obtém o valor personalizado do artefato. |
| set_value(name, value) | Define o valor personalizado do artefato. |
| remove_value(name) | Remove o valor personalizado do artefato. |
| begin_updates() | Inicie atualizações atrasadas. Use este recurso se precisar fazer várias alterações no mesmo artefato para melhorar o desempenho. <br/>            Normalmente os operadores de artefato são alterados sempre que a propriedade do artefato foi modificada. Isso causa a mudança do conteúdo da página<br/>            toda vez que o artefato foi alterado. Para evitar esse efeito, coloque todas as atualizações de artefato entre as chamadas StartUpdates/SaveUpdates.<br/>            Isso permite mudar o conteúdo da página apenas uma vez. |
| save_updates() | Salva todas as atualizações no artefato que foram feitas após a chamada BeginUpdates(). |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

