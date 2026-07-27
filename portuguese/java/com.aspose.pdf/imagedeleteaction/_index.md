---
title: "ImageDeleteAction"
linktitle: "ImageDeleteAction"
second_title: "Referência da API Aspose.PDF para Java"
description: "Ação que é executada com o objeto de imagem quando a imagem é removida da coleção. Se o objeto de imagem for removido"
type: docs
weight: 2290
url: /pt/java/com.aspose.pdf/imagedeleteaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.ImageDeleteAction, com.aspose.ms.System.Enum, com.aspose.pdf.ImageDeleteAction

```
public final class ImageDeleteAction extends com.aspose.ms.System.Enum
```

Ação que é executada com o objeto de imagem quando a imagem é removida da coleção. Se o objeto de imagem for removido

## Campos

| Campo | Descrição |
| --- | --- |
| [Check](#Check) | A imagem será removida da coleção e o objeto de imagem será removido somente se não houver outras referências à imagem em outras páginas. Isso pode exigir mais tempo em comparação com a opção ForceDelete. |
| [ForceDelete](#ForceDelete) | A imagem será removida da coleção e o objeto de imagem será removido do documento. Se existirem outras referências ao mesmo objeto, o documento pode ficar corrompido. |
| [KeepContents](#KeepContents) | A imagem será removida da coleção. Se o conteúdo da página contiver referências à imagem, elas não serão removidas. O documento pode ficar inválido. |
| [None](#None) | A imagem será removida da coleção e do conteúdo da página, mas o objeto de imagem não será excluído. O tamanho do arquivo não será reduzido. |

### Check {#Check}
```
public static final int Check
```

A imagem será removida da coleção e o objeto de imagem será removido somente se não houver outras referências à imagem em outras páginas. Isso pode exigir mais tempo em comparação com a opção ForceDelete.

### ForceDelete {#ForceDelete}
```
public static final int ForceDelete
```

A imagem será removida da coleção e o objeto de imagem será removido do documento. Se existirem outras referências ao mesmo objeto, o documento pode ficar corrompido.

### KeepContents {#KeepContents}
```
public static final int KeepContents
```

A imagem será removida da coleção. Se o conteúdo da página contiver referências à imagem, elas não serão removidas. O documento pode ficar inválido.

### None {#None}
```
public static final int None
```

A imagem será removida da coleção e do conteúdo da página, mas o objeto de imagem não será excluído. O tamanho do arquivo não será reduzido.
