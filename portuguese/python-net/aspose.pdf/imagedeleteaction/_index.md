---
title: "ImageDeleteAction"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Ação que é executada com o objeto de imagem quando a imagem é removida da coleção. Se o objeto de imagem for removido"
type: docs
weight: 6450
url: /pt/python-net/aspose.pdf/imagedeleteaction/
---

## ImageDeleteAction enumeration

Ação que é executada com o objeto de imagem quando a imagem é removida da coleção. Se o objeto de imagem for removido

## Members
| Nome do membro | Descrição |
| :- | :- |
| KEEP_CONTENTS | A imagem será removida da coleção. Se o conteúdo da página contiver referências à imagem, elas não serão removidas. O documento pode ficar inválido. |
| NONE | A imagem será removida da coleção e do conteúdo da página, mas o objeto de imagem não será excluído. O tamanho do arquivo não será reduzido. |
| FORCE_DELETE | A imagem será removida da coleção e o objeto de imagem será removido do documento. Se existirem outras referências ao mesmo objeto, o documento pode ficar corrompido. |
| CHECK | A imagem será removida da coleção e o objeto de imagem será removido somente se não houver outras referências à imagem em outras páginas. Isso pode exigir mais tempo em comparação com a opção Force Delete. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

