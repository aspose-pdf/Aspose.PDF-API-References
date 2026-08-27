---
title: "Elemento"
linktitle: "Elemento"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa o elemento base da estrutura lógica."
type: docs
weight: 1180
url: /pt/java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Element

```
public abstract class Element extends Object
```

Classe que representa o elemento base da estrutura lógica.

## Métodos

| Método | Descrição |
| --- | --- |
| [getActualText](#getActualText--) | (Opcional; PDF 1.4) Texto que é uma substituição exata para o elemento de estrutura e seus filhos. Este texto de substituição (que deve ser aplicado ao menor trecho de conteúdo possível) é útil ao extrair o conteúdo do documento em apoio à acessibilidade para usuários com deficiência ou para outros fins. |
| [getAlt](#getAlt--) | (Opcional) Uma descrição alternativa do elemento de estrutura e de seus filhos em forma legível por humanos, que é útil ao extrair o conteúdo do documento em apoio à acessibilidade para usuários com deficiência ou para outros fins. |
| [getChildren](#getChildren--) | Obtém a coleção de elementos filhos. |
| [getE](#getE--) | (Opcional; PDF 1.5) A forma expandida de uma abreviação. |
| [getLang](#getLang--) | (Opcional; PDF 1.4) Um idioma que especifica a língua natural para todo o texto no elemento de estrutura, exceto onde for sobrescrito por especificações de idioma para elementos de estrutura aninhados ou conteúdo marcado. |
| [remove](#remove--) | Remover elemento. |
| [setActualText](#setActualText-java.lang.String-) | (Opcional; PDF 1.4) Texto que é uma substituição exata para o elemento de estrutura e seus filhos. Este texto de substituição (que deve ser aplicado ao menor trecho de conteúdo possível) é útil ao extrair o conteúdo do documento em apoio à acessibilidade para usuários com deficiência ou para outros fins. |
| [setAlt](#setAlt-java.lang.String-) | (Opcional) Uma descrição alternativa do elemento de estrutura e de seus filhos em forma legível por humanos, que é útil ao extrair o conteúdo do documento em apoio à acessibilidade para usuários com deficiência ou para outros fins. |
| [setE](#setE-java.lang.String-) | (Opcional; PDF 1.5) A forma expandida de uma abreviação. |
| [setLang](#setLang-java.lang.String-) | (Opcional; PDF 1.4) Um idioma que especifica a língua natural para todo o texto no elemento de estrutura, exceto onde for sobrescrito por especificações de idioma para elementos de estrutura aninhados ou conteúdo marcado. |

### getActualText {#getActualText--}
```
public String getActualText()
```

(Opcional; PDF 1.4) Texto que é uma substituição exata para o elemento de estrutura e seus filhos. Este texto de substituição (que deve ser aplicado ao menor trecho de conteúdo possível) é útil ao extrair o conteúdo do documento em apoio à acessibilidade para usuários com deficiência ou para outros fins.

**Returns:**
Objeto String

### getAlt {#getAlt--}
```
public String getAlt()
```

(Opcional) Uma descrição alternativa do elemento de estrutura e de seus filhos em forma legível por humanos, que é útil ao extrair o conteúdo do documento em apoio à acessibilidade para usuários com deficiência ou para outros fins.

**Returns:**
Objeto String

### getChildren {#getChildren--}
```
public final ElementCollection getChildren()
```

Obtém a coleção de elementos filhos.

**Returns:**
Instância de ElementCollection

### getE {#getE--}
```
public String getE()
```

(Opcional; PDF 1.5) A forma expandida de uma abreviação.

**Returns:**
Objeto String

### getLang {#getLang--}
```
public String getLang()
```

(Opcional; PDF 1.4) Um idioma que especifica a língua natural para todo o texto no elemento de estrutura, exceto onde for sobrescrito por especificações de idioma para elementos de estrutura aninhados ou conteúdo marcado.

**Returns:**
Objeto String

### remove {#remove--}
```
public final void remove()
```

Remover elemento.

### setActualText {#setActualText-java.lang.String-}
(Opcional; PDF 1.4) Texto que é uma substituição exata para o elemento de estrutura e seus filhos. Este texto de substituição (que deve ser aplicado ao menor trecho de conteúdo possível) é útil ao extrair o conteúdo do documento em apoio à acessibilidade para usuários com deficiência ou para outros fins.

### setAlt {#setAlt-java.lang.String-}
(Opcional) Uma descrição alternativa do elemento de estrutura e de seus filhos em forma legível por humanos, que é útil ao extrair o conteúdo do documento em apoio à acessibilidade para usuários com deficiência ou para outros fins.

### setE {#setE-java.lang.String-}
(Opcional; PDF 1.5) A forma expandida de uma abreviação.

### setLang {#setLang-java.lang.String-}
(Opcional; PDF 1.4) Um idioma que especifica a língua natural para todo o texto no elemento de estrutura, exceto onde for sobrescrito por especificações de idioma para elementos de estrutura aninhados ou conteúdo marcado.
