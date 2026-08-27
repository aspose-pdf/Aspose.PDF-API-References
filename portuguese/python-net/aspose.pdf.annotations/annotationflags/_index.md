---
title: "AnnotationFlags"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Um conjunto de sinalizadores que especificam várias características da anotação."
type: docs
weight: 930
url: /pt/python-net/aspose.pdf.annotations/annotationflags/
---

## AnnotationFlags enumeration

Um conjunto de sinalizadores que especificam várias características da anotação.

## Members
| Nome do membro | Descrição |
| :- | :- |
| DEFAULT | Valor padrão. |
| INVISIBLE | Se definido, não exiba a anotação se ela não pertencer a um dos tipos padrão de anotação<br/>            e nenhum manipulador de anotação estiver disponível. Se não definido, exiba essa anotação desconhecida<br/>            usando um fluxo de aparência especificado por seu dicionário de aparência, se houver. |
| HIDDEN | Se definido, não exiba nem imprima a anotação nem permita que ela interaja com o usuário,<br/>            independentemente do tipo de anotação ou da disponibilidade de um manipulador de anotação.<br/>            Em casos onde o espaço na tela é limitado, a capacidade de ocultar e mostrar anotações seletivamente<br/>            pode ser usada em combinação com fluxos de aparência para exibir informações auxiliares em pop‑up<br/>            semelhantes em função a sistemas de ajuda online. |
| IMPRIMIR | Se definido, imprima a anotação quando a página for impressa. Se não definido, nunca imprima a anotação,<br/>            independentemente de estar exibida na tela. Isso pode ser útil, por exemplo, para anotações<br/>            que representam botões interativos, que não teriam propósito significativo na página impressa. |
| NO_ZOOM | Se definido, não escale a aparência da anotação para corresponder à ampliação da página.<br/>            A localização da anotação na página (definida pelo canto superior esquerdo de seu retângulo de anotação)<br/>            permanece fixa, independentemente da ampliação da página. |
| NO_ROTATE | Se definido, não rotacione a aparência da anotação para corresponder à rotação da página.<br/>            O canto superior esquerdo do retângulo da anotação permanece em uma posição fixa na página,<br/>            independentemente da rotação da página. |
| NO_VIEW | Se definido, não exiba a anotação na tela nem permita que ela interaja com o usuário.<br/>            A anotação pode ser impressa (dependendo da configuração da flag Print)<br/>            mas deve ser considerada oculta para fins de exibição na tela e interação do usuário. |
| READ_ONLY | Se definido, não permita que a anotação interaja com o usuário. A anotação pode ser exibida<br/>            ou impressa (dependendo das configurações das flags NoView e Print), mas não deve responder a cliques<br/>            do mouse ou alterar sua aparência em resposta a movimentos do mouse. Essa flag é ignorada para anotações de widget;<br/>            sua função é absorvida pela flag ReadOnly do campo de formulário associado. |
| LOCKED | Se definido, não permita que a anotação seja excluída ou que suas propriedades (incluindo posição e tamanho)<br/>            sejam modificadas pelo usuário. No entanto, essa flag não restringe alterações no conteúdo da anotação,<br/>            como o valor de um campo de formulário. |
| TOGGLE_NO_VIEW | Se definido, inverte a interpretação da bandeira NoView para certos eventos.<br/>            Um uso típico é ter uma anotação que aparece somente quando o cursor do mouse está sobre ela. |
| LOCKED_CONTENTS | Se definido, não permite que o conteúdo da anotação seja modificado pelo usuário.<br/>            Esta bandeira não restringe a exclusão da anotação ou alterações em outras propriedades da anotação,<br/>            como posição e tamanho. |

### Veja Também

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

