---
title: "XfaParserOptions"
linktitle: "XfaParserOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "classe para lidar com a encapsulação de dados relacionados"
type: docs
weight: 5560
url: /pt/java/com.aspose.pdf/xfaparseroptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfaParserOptions

```
public class XfaParserOptions extends Object
```

classe para lidar com a encapsulação de dados relacionados

## Construtores

| Construtor | Descrição |
| --- | --- |
| [XfaParserOptions](#XfaParserOptions-java.awt.geom.Dimension2D-) | Inicializa uma nova instância da classe {@code XfaParserOptions}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBasePath](#getBasePath--) | Obtém ou define o caminho base. Valor: O caminho base. |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Se esta propriedade for verdadeira, retângulos vermelhos adicionais serão desenhados para os \"grupos excluídos\" Xfa necessários. Esta propriedade foi introduzida porque a ausência de analogias dos grupos excluídos durante a conversão da representação Xfa de formulários para o padrão. É falsa por padrão. |
| [getPageSize](#getPageSize--) | Obtém ou define o tamanho da página. Valor: O tamanho da página. |
| [getSigned](#getSigned--) | Se esta propriedade for verdadeira, o documento será convertido usando o fluxo de formulário xfa (se existir). Se for falsa, o fluxo de formulário xfa será ignorado. Esta propriedade foi introduzida porque não está claro como calcular a soma de verificação usada para verificar a assinatura. |
| [setBasePath](#setBasePath-java.net.URI-) | Obtém ou define o caminho base. Valor: O caminho base. |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Se esta propriedade for verdadeira, retângulos vermelhos adicionais serão desenhados para os \"grupos excluídos\" Xfa necessários. Esta propriedade foi introduzida porque a ausência de analogias dos grupos excluídos durante a conversão da representação Xfa de formulários para o padrão. É falsa por padrão. |
| [setPageSize](#setPageSize-java.awt.geom.Dimension2D-) | Obtém ou define o tamanho da página. Valor: O tamanho da página. |
| [setSigned](#setSigned-boolean-) | Se esta propriedade for verdadeira, o documento será convertido usando o fluxo de formulário xfa (se existir). Se for falsa, o fluxo de formulário xfa será ignorado. Esta propriedade foi introduzida porque não está claro como calcular a soma de verificação usada para verificar a assinatura. |

### XfaParserOptions {#XfaParserOptions-java.awt.geom.Dimension2D-}
Inicializa uma nova instância da classe {@code XfaParserOptions}.

### getBasePath {#getBasePath--}
```
public URI getBasePath()
```

Obtém ou define o caminho base. Valor: O caminho base.

**Returns:**
Objeto URI

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Se esta propriedade for verdadeira, retângulos vermelhos adicionais serão desenhados para os \"grupos excluídos\" Xfa necessários. Esta propriedade foi introduzida porque a ausência de analogias dos grupos excluídos durante a conversão da representação Xfa de formulários para o padrão. É falsa por padrão.

**Returns:**
valor booleano

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

Obtém ou define o tamanho da página. Valor: O tamanho da página.

**Returns:**
Objeto Dimension2D

### getSigned {#getSigned--}
```
public boolean getSigned()
```

Se esta propriedade for verdadeira, o documento será convertido usando o fluxo de formulário xfa (se existir). Se for falsa, o fluxo de formulário xfa será ignorado. Esta propriedade foi introduzida porque não está claro como calcular a soma de verificação usada para verificar a assinatura.

**Returns:**
valor booleano

### setBasePath {#setBasePath-java.net.URI-}
Obtém ou define o caminho base. Valor: O caminho base.

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Se esta propriedade for verdadeira, retângulos vermelhos adicionais serão desenhados para os \"grupos excluídos\" Xfa necessários. Esta propriedade foi introduzida porque a ausência de analogias dos grupos excluídos durante a conversão da representação Xfa de formulários para o padrão. É falsa por padrão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setPageSize {#setPageSize-java.awt.geom.Dimension2D-}
Obtém ou define o tamanho da página. Valor: O tamanho da página.

### setSigned {#setSigned-boolean-}
```
public void setSigned(boolean value)
```

Se esta propriedade for verdadeira, o documento será convertido usando o fluxo de formulário xfa (se existir). Se for falsa, o fluxo de formulário xfa será ignorado. Esta propriedade foi introduzida porque não está claro como calcular a soma de verificação usada para verificar a assinatura.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
