---
title: "Permissões"
linktitle: "Permissões"
second_title: "Referência da API Aspose.PDF para Java"
description: "Flag binária. Esta enumeração representa as permissões do usuário para um pdf."
type: docs
weight: 3830
url: /pt/java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

Flag binária. Esta enumeração representa as permissões do usuário para um pdf.

## Campos

| Campo | Descrição |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | (Manipuladores de segurança da revisão 3 ou superior) Montar o documento (inserir, girar ou excluir páginas e criar marcadores ou imagens em miniatura), mesmo que {@code ModifyContent} esteja claro. |
| [ExtractContent](#ExtractContent) | (Manipuladores de segurança da revisão 2) Copiar ou extrair texto e gráficos do documento, incluindo a extração de texto e gráficos (em apoio à acessibilidade para usuários com deficiência ou para outros fins). (Manipuladores de segurança da revisão 3 ou superior) Copiar ou extrair texto e gráficos do documento por operações diferentes daquelas controladas por {@code ExtractContentWithDisabilities}. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (Manipuladores de segurança da revisão 3 ou superior) Extrair texto e gráficos (em apoio à acessibilidade para usuários com deficiência ou para outros fins). |
| [FillForm](#FillForm) | (Manipuladores de segurança da revisão 3 ou superior) Preencher campos de formulário interativo existentes (incluindo campos de assinatura), mesmo que {@code ModifyTextAnnotations} esteja claro. |
| [ModifyContent](#ModifyContent) | Modificar o conteúdo do documento por operações diferentes daquelas controladas por {@code ModifyTextAnnotations}, {@code FillForm} e 11. |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | Adicionar ou modificar anotações de texto, preencher campos de formulário interativo e, se {@code ModifyContent} também estiver definido, criar ou modificar campos de formulário interativo (incluindo campos de assinatura). |
| [PrintDocument](#PrintDocument) | (Manipuladores de segurança da revisão 2) Imprimir o documento. (Manipuladores de segurança da revisão 3 ou superior) Imprimir o documento (possivelmente não no nível de qualidade mais alto, dependendo se {@code PrintingQuality} também estiver definido). |
| [PrintingQuality](#PrintingQuality) | (Manipuladores de segurança da revisão 3 ou superior) Imprima o documento para uma representação a partir da qual uma cópia digital fiel do conteúdo PDF possa ser gerada. Quando este bit está limpo (e o bit 3 está definido), a impressão é limitada a uma representação de baixo nível da aparência, possivelmente de qualidade degradada. |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

(Manipuladores de segurança da revisão 3 ou superior) Montar o documento (inserir, girar ou excluir páginas e criar marcadores ou imagens em miniatura), mesmo que {@code ModifyContent} esteja claro.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(Manipuladores de segurança da revisão 2) Copiar ou extrair texto e gráficos do documento, incluindo a extração de texto e gráficos (em apoio à acessibilidade para usuários com deficiência ou para outros fins). (Manipuladores de segurança da revisão 3 ou superior) Copiar ou extrair texto e gráficos do documento por operações diferentes daquelas controladas por {@code ExtractContentWithDisabilities}.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(Manipuladores de segurança da revisão 3 ou superior) Extrair texto e gráficos (em apoio à acessibilidade para usuários com deficiência ou para outros fins).

### FillForm {#FillForm}
```
public static final int FillForm
```

(Manipuladores de segurança da revisão 3 ou superior) Preencher campos de formulário interativo existentes (incluindo campos de assinatura), mesmo que {@code ModifyTextAnnotations} esteja claro.

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Modificar o conteúdo do documento por operações diferentes daquelas controladas por {@code ModifyTextAnnotations}, {@code FillForm} e 11.

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

Adicionar ou modificar anotações de texto, preencher campos de formulário interativo e, se {@code ModifyContent} também estiver definido, criar ou modificar campos de formulário interativo (incluindo campos de assinatura).

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(Manipuladores de segurança da revisão 2) Imprimir o documento. (Manipuladores de segurança da revisão 3 ou superior) Imprimir o documento (possivelmente não no nível de qualidade mais alto, dependendo se {@code PrintingQuality} também estiver definido).

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(Manipuladores de segurança da revisão 3 ou superior) Imprima o documento para uma representação a partir da qual uma cópia digital fiel do conteúdo PDF possa ser gerada. Quando este bit está limpo (e o bit 3 está definido), a impressão é limitada a uma representação de baixo nível da aparência, possivelmente de qualidade degradada.
