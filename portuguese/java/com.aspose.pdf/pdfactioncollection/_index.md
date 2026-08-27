---
title: "PdfActionCollection"
linktitle: "PdfActionCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe descreve lista de ações."
type: docs
weight: 3680
url: /pt/java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

Classe descreve lista de ações.

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Adiciona ação à lista de ações. |
| [delete](#delete-int-) | Remove ação por índice. |
| [get_Item](#get_Item-int-) | Obtém ação pelo seu índice. |
| [getCount](#getCount--) | Obtém a contagem de ações. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Método interno |
| [iterator](#iterator--) | Obtém enumerador. |

### add {#add-com.aspose.pdf.PdfAction-}
Adiciona ação à lista de ações.

### delete {#delete-int-}
```
public void delete(int index)
```

Remove ação por índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice da ação a remover. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

Obtém ação pelo seu índice.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Valor do índice da ação. |

**Returns:**
Índice do PdfAction se encontrado; caso contrário, lança @throws IndexOutOfRangeException IndexOutOfRangeException

### getCount {#getCount--}
```
public int getCount()
```

Obtém a contagem de ações.

**Returns:**
valor int

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

Método interno

**Returns:**
objeto interno.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

Obtém enumerador.

**Returns:**
enumerador PDfAction.
