---
title: Enum AnnotationFlags
second_title: Aspose.PDF for .NET API Reference
description: Enum AnnotationFlags do Aspose.Pdf.Annotations. Um conjunto de flags especificando várias características da anotação
type: docs
weight: 1440
url: /pt/net/aspose.pdf.annotations/annotationflags/
---
## Enumeração AnnotationFlags

Um conjunto de flags especificando várias características da anotação.

```csharp
[Flags]
public enum AnnotationFlags
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Default | `0` | Valor padrão. |
| Invisible | `1` | Se definido, não exiba a anotação se ela não pertencer a um dos tipos de anotação padrão e nenhum manipulador de anotação estiver disponível. Se limpo, exiba tal anotação desconhecida usando um fluxo de aparência especificado por seu dicionário de aparência, se houver. |
| Hidden | `2` | Se definido, não exiba ou imprima a anotação ou permita que ela interaja com o usuário, independentemente de seu tipo de anotação ou se um manipulador de anotação estiver disponível. Em casos onde o espaço na tela é limitado, a capacidade de ocultar e mostrar anotações seletivamente pode ser usada em combinação com fluxos de aparência para exibir informações pop-up auxiliares semelhantes em função aos sistemas de ajuda online. |
| Print | `4` | Se definido, imprima a anotação quando a página for impressa. Se limpo, nunca imprima a anotação, independentemente de ela ser exibida na tela. Isso pode ser útil, por exemplo, para anotações que representam botões interativos, que não teriam propósito significativo na página impressa. |
| NoZoom | `8` | Se definido, não escale a aparência da anotação para corresponder à ampliação da página. A localização da anotação na página (definida pelo canto superior esquerdo de seu retângulo de anotação) permanece fixa, independentemente da ampliação da página. |
| NoRotate | `10` | Se definido, não gire a aparência da anotação para corresponder à rotação da página. O canto superior esquerdo do retângulo da anotação permanece em uma localização fixa na página, independentemente da rotação da página. |
| NoView | `20` | Se definido, não exiba a anotação na tela ou permita que ela interaja com o usuário. A anotação pode ser impressa (dependendo da configuração da flag Print), mas deve ser considerada oculta para fins de exibição na tela e interação do usuário. |
| ReadOnly | `40` | Se definido, não permita que a anotação interaja com o usuário. A anotação pode ser exibida ou impressa (dependendo das configurações das flags NoView e Print), mas não deve responder a cliques do mouse ou mudar sua aparência em resposta a movimentos do mouse. Esta flag é ignorada para anotações de widget; sua função é absorvida pela flag ReadOnly do campo de formulário associado. |
| Locked | `80` | Se definido, não permita que a anotação seja deletada ou que suas propriedades (incluindo posição e tamanho) sejam modificadas pelo usuário. No entanto, esta flag não restringe alterações ao conteúdo da anotação, como o valor de um campo de formulário. |
| ToggleNoView | `100` | Se definido, inverta a interpretação da flag NoView para certos eventos. Um uso típico é ter uma anotação que aparece apenas quando um cursor do mouse está sobre ela. |
| LockedContents | `200` | Se definido, não permita que o conteúdo da anotação seja modificado pelo usuário. Esta flag não restringe a exclusão da anotação ou alterações a outras propriedades da anotação, como posição e tamanho. |

### Veja Também

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)