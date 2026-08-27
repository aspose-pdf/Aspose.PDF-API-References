---
title: "AnnotationFlags"
linktitle: "AnnotationFlags"
second_title: "Referência da API Aspose.PDF para Java"
description: "Flags Um conjunto de bandeiras binárias que especificam várias características da anotação."
type: docs
weight: 90
url: /pt/java/com.aspose.pdf/annotationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.Enum, com.aspose.pdf.AnnotationFlags

```
public final class AnnotationFlags extends com.aspose.ms.System.Enum
```

Flags Um conjunto de bandeiras binárias que especificam várias características da anotação.

## Campos

| Campo | Descrição |
| --- | --- |
| [Default](#Default) | Valor padrão. |
| [Hidden](#Hidden) | Se definido, não exiba ou imprima a anotação nem permita que ela interaja com o usuário, independentemente do tipo de anotação ou da disponibilidade de um manipulador de anotações. Nos casos em que o espaço de tela é limitado, a capacidade de ocultar e mostrar anotações seletivamente pode ser usada em combinação com fluxos de aparência para exibir informações auxiliares em pop‑up semelhantes em função a sistemas de ajuda online. |
| [Invisible](#Invisible) | Se definido, não exiba a anotação se ela não pertencer a um dos tipos padrão de anotação e nenhum manipulador de anotação estiver disponível. Se desmarcado, exiba essa anotação desconhecida usando um fluxo de aparência especificado por seu dicionário de aparência, se houver. |
| [Locked](#Locked) | Se definido, não permita que a anotação seja excluída ou que suas propriedades (incluindo posição e tamanho) sejam modificadas pelo usuário. No entanto, essa flag não restringe alterações no conteúdo da anotação, como o valor de um campo de formulário. |
| [LockedContents](#LockedContents) | Se definido, não permita que o conteúdo da anotação seja modificado pelo usuário. Esta flag não restringe a exclusão da anotação ou alterações em outras propriedades da anotação, como posição e tamanho. |
| [NoRotate](#NoRotate) | Se definido, não gire a aparência da anotação para corresponder à rotação da página. O canto superior esquerdo do retângulo da anotação permanece em uma posição fixa na página, independentemente da rotação da página. |
| [NoView](#NoView) | Se definido, não exiba a anotação na tela nem permita que ela interaja com o usuário. A anotação pode ser impressa (dependendo da configuração da flag Print), mas deve ser considerada oculta para fins de exibição na tela e interação do usuário. |
| [NoZoom](#NoZoom) | Se definido, não escale a aparência da anotação para corresponder à ampliação da página. A localização da anotação na página (definida pelo canto superior esquerdo de seu retângulo de anotação) permanece fixa, independentemente da ampliação da página. |
| [Print](#Print) | Se definido, imprima a anotação quando a página for impressa. Se desmarcado, nunca imprima a anotação, independentemente de ser exibida na tela. Isso pode ser útil, por exemplo, para anotações que representam botões interativos, que não teriam propósito significativo na página impressa. |
| [ReadOnly](#ReadOnly) | Se definido, não permita que a anotação interaja com o usuário. A anotação pode ser exibida ou impressa (dependendo das configurações das flags NoView e Print), mas não deve responder a cliques do mouse ou mudar sua aparência em resposta a movimentos do mouse. Essa flag é ignorada para anotações de widget; sua função é absorvida pela flag ReadOnly do campo de formulário associado. |
| [ToggleNoView](#ToggleNoView) | Se definido, inverta a interpretação da flag NoView para certos eventos. Um uso típico é ter uma anotação que aparece somente quando o cursor do mouse é mantido sobre ela. |

### Default {#Default}
```
public static final int Default
```

Valor padrão.

### Hidden {#Hidden}
```
public static final int Hidden
```

Se definido, não exiba ou imprima a anotação nem permita que ela interaja com o usuário, independentemente do tipo de anotação ou da disponibilidade de um manipulador de anotações. Nos casos em que o espaço de tela é limitado, a capacidade de ocultar e mostrar anotações seletivamente pode ser usada em combinação com fluxos de aparência para exibir informações auxiliares em pop‑up semelhantes em função a sistemas de ajuda online.

### Invisible {#Invisible}
```
public static final int Invisible
```

Se definido, não exiba a anotação se ela não pertencer a um dos tipos padrão de anotação e nenhum manipulador de anotação estiver disponível. Se desmarcado, exiba essa anotação desconhecida usando um fluxo de aparência especificado por seu dicionário de aparência, se houver.

### Locked {#Locked}
```
public static final int Locked
```

Se definido, não permita que a anotação seja excluída ou que suas propriedades (incluindo posição e tamanho) sejam modificadas pelo usuário. No entanto, essa flag não restringe alterações no conteúdo da anotação, como o valor de um campo de formulário.

### LockedContents {#LockedContents}
```
public static final int LockedContents
```

Se definido, não permita que o conteúdo da anotação seja modificado pelo usuário. Esta flag não restringe a exclusão da anotação ou alterações em outras propriedades da anotação, como posição e tamanho.

### NoRotate {#NoRotate}
```
public static final int NoRotate
```

Se definido, não gire a aparência da anotação para corresponder à rotação da página. O canto superior esquerdo do retângulo da anotação permanece em uma posição fixa na página, independentemente da rotação da página.

### NoView {#NoView}
```
public static final int NoView
```

Se definido, não exiba a anotação na tela nem permita que ela interaja com o usuário. A anotação pode ser impressa (dependendo da configuração da flag Print), mas deve ser considerada oculta para fins de exibição na tela e interação do usuário.

### NoZoom {#NoZoom}
```
public static final int NoZoom
```

Se definido, não escale a aparência da anotação para corresponder à ampliação da página. A localização da anotação na página (definida pelo canto superior esquerdo de seu retângulo de anotação) permanece fixa, independentemente da ampliação da página.

### Print {#Print}
```
public static final int Print
```

Se definido, imprima a anotação quando a página for impressa. Se desmarcado, nunca imprima a anotação, independentemente de ser exibida na tela. Isso pode ser útil, por exemplo, para anotações que representam botões interativos, que não teriam propósito significativo na página impressa.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```

Se definido, não permita que a anotação interaja com o usuário. A anotação pode ser exibida ou impressa (dependendo das configurações das flags NoView e Print), mas não deve responder a cliques do mouse ou mudar sua aparência em resposta a movimentos do mouse. Essa flag é ignorada para anotações de widget; sua função é absorvida pela flag ReadOnly do campo de formulário associado.

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```

Se definido, inverta a interpretação da flag NoView para certos eventos. Um uso típico é ter uma anotação que aparece somente quando o cursor do mouse é mantido sobre ela.
