---
title: "PageLabelCollection"
linktitle: "PageLabelCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa a coleção de rótulos de página."
type: docs
weight: 3400
url: /pt/java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

Classe que representa a coleção de rótulos de página.

## Métodos

| Método | Descrição |
| --- | --- |
| [getLabel](#getLabel-int-) | Obtém o rótulo da página pelo índice da página (o índice da página começa em 0). |
| [getPages](#getPages--) | Obtém os índices das páginas na coleção. |
| [removeLabel](#removeLabel-int-) | Remove o rótulo pelo índice da página (o índice da página começa em 0). |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | Atualiza o rótulo para o índice de página fornecido (o índice da página começa em 0). |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

Obtém o rótulo da página pelo índice da página (o índice da página começa em 0).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageIndex |  | Índice da página. |

**Returns:**
Rótulo da página para o índice de página especificado ou null se o rótulo da página não existir.

### getPages {#getPages--}
```
public int[] getPages()
```

Obtém os índices das páginas na coleção.

**Returns:**
Array de inteiros que contém os índices das páginas.

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

Remove o rótulo pelo índice da página (o índice da página começa em 0).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageIndex |  | Índice da página onde o rótulo deve ser excluído. |

**Returns:**
true se a operação foi executada com sucesso.

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
Atualiza o rótulo para o índice de página fornecido (o índice da página começa em 0).
