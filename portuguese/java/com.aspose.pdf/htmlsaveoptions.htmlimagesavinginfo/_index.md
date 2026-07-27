---
title: "HtmlSaveOptions.HtmlImageSavingInfo"
linktitle: "HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta classe representa um conjunto de dados relacionados ao salvamento de arquivos de imagem de recursos externos durante a conversão de PDF para HTML."
type: docs
weight: 2070
url: /pt/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

Esta classe representa um conjunto de dados relacionados ao salvamento de arquivos de imagem de recursos externos durante a conversão de PDF para HTML.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | cria nova instância de HtmlImageSavingInfo |

## Métodos

| Método | Descrição |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Indica ao código personalizado a que página do conjunto gerado de arquivos HTML a imagem salva se refere. Se a divisão em páginas estiver desativada, este valor sempre contém '1', pois nesse caso apenas uma página HTML é gerada. |
| [getImageType](#getImageType--) | Representa o tipo de imagem salva referenciada em HTML. Definido pelo conversor e pode ser usado no código personalizado para decidir o que deve ser feito. |
| [getParentType](#getParentType--) | A imagem salva pode pertencer ao próprio HTML ou pode ser extraída de SVG incorporado ao HTML. Esta propriedade pode informar ao código personalizado qual é o tipo de pai da imagem processada. É definida pelo conversor e pode ser usada no código personalizado para decidir o que deve ser feito com essa imagem (por exemplo, o código personalizado pode decidir onde salvar a imagem ou como ela deve ser referenciada no conteúdo do pai). |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Indica ao código personalizado a que página do documento PDF original a imagem salva se refere. Como é possível que nem todas as páginas do documento original sejam salvas, este valor informa o número da página hospedeira no PDF original. Se o número da página original for desconhecido por algum motivo, ele sempre retorna '1'. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Indica ao código personalizado a que página do conjunto gerado de arquivos HTML a imagem salva se refere. Se a divisão em páginas estiver desativada, este valor sempre contém '1', pois nesse caso apenas uma página HTML é gerada. |
| [setImageType](#setImageType-int-) | Representa o tipo de imagem salva referenciada em HTML. Definido pelo conversor e pode ser usado no código personalizado para decidir o que deve ser feito. |
| [setParentType](#setParentType-int-) | A imagem salva pode pertencer ao próprio HTML ou pode ser extraída de SVG incorporado ao HTML. Esta propriedade pode informar ao código personalizado qual é o tipo de pai da imagem processada. É definida pelo conversor e pode ser usada no código personalizado para decidir o que deve ser feito com essa imagem (por exemplo, o código personalizado pode decidir onde salvar a imagem ou como ela deve ser referenciada no conteúdo do pai). |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Indica ao código personalizado a que página do documento PDF original a imagem salva se refere. Como é possível que nem todas as páginas do documento original sejam salvas, este valor informa o número da página hospedeira no PDF original. Se o número da página original for desconhecido por algum motivo, ele sempre retorna '1'. |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

cria nova instância de HtmlImageSavingInfo

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Indica ao código personalizado a que página do conjunto gerado de arquivos HTML a imagem salva se refere. Se a divisão em páginas estiver desativada, este valor sempre contém '1', pois nesse caso apenas uma página HTML é gerada.

**Returns:**
valor int

### getImageType {#getImageType--}
```
public int getImageType()
```

Representa o tipo de imagem salva referenciada em HTML. Definido pelo conversor e pode ser usado no código personalizado para decidir o que deve ser feito.

**Returns:**
Elemento HtmlImageType @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

A imagem salva pode pertencer ao próprio HTML ou pode ser extraída de SVG incorporado ao HTML. Esta propriedade pode informar ao código personalizado qual é o tipo de pai da imagem processada. É definida pelo conversor e pode ser usada no código personalizado para decidir o que deve ser feito com essa imagem (por exemplo, o código personalizado pode decidir onde salvar a imagem ou como ela deve ser referenciada no conteúdo do pai).

**Returns:**
Elemento ImageParentTypes @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Indica ao código personalizado a que página do documento PDF original a imagem salva se refere. Como é possível que nem todas as páginas do documento original sejam salvas, este valor informa o número da página hospedeira no PDF original. Se o número da página original for desconhecido por algum motivo, ele sempre retorna '1'.

**Returns:**
valor int

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Indica ao código personalizado a que página do conjunto gerado de arquivos HTML a imagem salva se refere. Se a divisão em páginas estiver desativada, este valor sempre contém '1', pois nesse caso apenas uma página HTML é gerada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| htmlHostPageNumber |  | valor int |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

Representa o tipo de imagem salva referenciada em HTML. Definido pelo conversor e pode ser usado no código personalizado para decidir o que deve ser feito.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageType |  | Elemento HtmlImageType @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

A imagem salva pode pertencer ao próprio HTML ou pode ser extraída de SVG incorporado ao HTML. Esta propriedade pode informar ao código personalizado qual é o tipo de pai da imagem processada. É definida pelo conversor e pode ser usada no código personalizado para decidir o que deve ser feito com essa imagem (por exemplo, o código personalizado pode decidir onde salvar a imagem ou como ela deve ser referenciada no conteúdo do pai).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| parentType |  | Elemento ImageParentTypes @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Indica ao código personalizado a que página do documento PDF original a imagem salva se refere. Como é possível que nem todas as páginas do documento original sejam salvas, este valor informa o número da página hospedeira no PDF original. Se o número da página original for desconhecido por algum motivo, ele sempre retorna '1'.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pdfHostPageNumber |  | valor int |
