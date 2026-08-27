---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "Referência da API Aspose.PDF para Java"
description: "Fornece configurações para a funcionalidade de auto‑tagging em documentos PDF. A classe {@link AutoTaggingSettings} permite configurar opções para a etiquetagem automática do conteúdo PDF. Ela."
type: docs
weight: 230
url: /pt/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

Fornece configurações para a funcionalidade de autoetiquetagem em documentos PDF. A classe {@link AutoTaggingSettings} permite configurar opções para a etiquetagem automática do conteúdo PDF. Ela inclui propriedades para habilitar ou desabilitar a autoetiquetagem, especificar uma estratégia para reconhecimento de títulos e definir níveis de título com base no tamanho das fontes.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getDefault](#getDefault--) | Obtém as configurações padrão para a funcionalidade de auto‑tagging em documentos PDF. As configurações padrão habilitam o auto‑tagging e utilizam a estratégia automática para reconhecimento de títulos. Essas configurações podem ser usadas como uma configuração de base para conversão de formato PDF ou outras operações que requerem a etiquetagem automática do conteúdo PDF. |
| [getEnableAutoTagging](#getEnableAutoTagging--) | Obtém ou define um valor que indica se a funcionalidade de auto‑tagging está habilitada. Quando habilitada, a funcionalidade de auto‑tagging gera automaticamente conteúdo etiquetado para o documento PDF, o que pode melhorar a acessibilidade e a estrutura. |
| [getHeadingLevels](#getHeadingLevels--) | Obtém ou define os níveis de título usados para determinar a estrutura dos títulos em um documento PDF. A propriedade {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permite configurar o mapeamento de tamanhos de fonte para níveis de título. Isso é usado durante o processo de auto‑tagging para identificar e atribuir níveis de título apropriados com base no tamanho da fonte dos elementos de texto no documento. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Obtém ou define a estratégia usada para reconhecer títulos no documento durante a marcação automática. A propriedade {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina como os títulos são identificados no documento. As estratégias disponíveis incluem reconhecer títulos com base em contornos, análise heurística ou detecção automática. Definir esta propriedade para {@link HeadingRecognitionStrategy#None} desativa o reconhecimento de títulos. |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | Obtém ou define um valor que indica se a funcionalidade de auto‑tagging está habilitada. Quando habilitada, a funcionalidade de auto‑tagging gera automaticamente conteúdo etiquetado para o documento PDF, o que pode melhorar a acessibilidade e a estrutura. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Obtém ou define os níveis de título usados para determinar a estrutura dos títulos em um documento PDF. A propriedade {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permite configurar o mapeamento de tamanhos de fonte para níveis de título. Isso é usado durante o processo de auto‑tagging para identificar e atribuir níveis de título apropriados com base no tamanho da fonte dos elementos de texto no documento. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Obtém ou define a estratégia usada para reconhecer títulos no documento durante a marcação automática. A propriedade {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina como os títulos são identificados no documento. As estratégias disponíveis incluem reconhecer títulos com base em contornos, análise heurística ou detecção automática. Definir esta propriedade para {@link HeadingRecognitionStrategy#None} desativa o reconhecimento de títulos. |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

Obtém as configurações padrão para a funcionalidade de auto‑tagging em documentos PDF. As configurações padrão habilitam o auto‑tagging e utilizam a estratégia automática para reconhecimento de títulos. Essas configurações podem ser usadas como uma configuração de base para conversão de formato PDF ou outras operações que requerem a etiquetagem automática do conteúdo PDF.

**Returns:**
Instância de AutoTaggingSettings

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

Obtém ou define um valor que indica se a funcionalidade de auto‑tagging está habilitada. Quando habilitada, a funcionalidade de auto‑tagging gera automaticamente conteúdo etiquetado para o documento PDF, o que pode melhorar a acessibilidade e a estrutura.

**Returns:**
valor booleano

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Obtém ou define os níveis de título usados para determinar a estrutura dos títulos em um documento PDF. A propriedade {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permite configurar o mapeamento de tamanhos de fonte para níveis de título. Isso é usado durante o processo de auto‑tagging para identificar e atribuir níveis de título apropriados com base no tamanho da fonte dos elementos de texto no documento.

**Returns:**
Instância de HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Obtém ou define a estratégia usada para reconhecer títulos no documento durante a marcação automática. A propriedade {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina como os títulos são identificados no documento. As estratégias disponíveis incluem reconhecer títulos com base em contornos, análise heurística ou detecção automática. Definir esta propriedade para {@link HeadingRecognitionStrategy#None} desativa o reconhecimento de títulos.

**Returns:**
Elemento HeadingRecognitionStrategy

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

Obtém ou define um valor que indica se a funcionalidade de auto‑tagging está habilitada. Quando habilitada, a funcionalidade de auto‑tagging gera automaticamente conteúdo etiquetado para o documento PDF, o que pode melhorar a acessibilidade e a estrutura.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Obtém ou define os níveis de título usados para determinar a estrutura dos títulos em um documento PDF. A propriedade {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permite configurar o mapeamento de tamanhos de fonte para níveis de título. Isso é usado durante o processo de auto‑tagging para identificar e atribuir níveis de título apropriados com base no tamanho da fonte dos elementos de texto no documento.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Obtém ou define a estratégia usada para reconhecer títulos no documento durante a marcação automática. A propriedade {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina como os títulos são identificados no documento. As estratégias disponíveis incluem reconhecer títulos com base em contornos, análise heurística ou detecção automática. Definir esta propriedade para {@link HeadingRecognitionStrategy#None} desativa o reconhecimento de títulos.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Elemento HeadingRecognitionStrategy |
