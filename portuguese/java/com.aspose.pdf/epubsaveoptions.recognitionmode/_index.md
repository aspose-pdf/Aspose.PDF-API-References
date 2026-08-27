---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "Referência da API Aspose.PDF para Java"
description: "Quando o arquivo PDF (que geralmente tem layout fixo) está sendo convertido, o mecanismo de conversão tenta realizar agrupamento e análise multinível para restaurar o documento original."
type: docs
weight: 1250
url: /pt/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

Quando um arquivo PDF (que geralmente tem layout fixo) está sendo convertido, o motor de conversão tenta realizar agrupamento e análise multinível para restaurar a intenção original do autor do documento e produzir o resultado em layout fluido. Esta propriedade ajusta essa conversão para o método desejável de reconhecimento de conteúdo.

## Campos

| Campo | Descrição |
| --- | --- |
| [Fixed](#Fixed) | Este modo é rápido e bom para preservar ao máximo a aparência original das páginas, mas infelizmente muitos leitores de EPUB não suportam xhtml com layout fixo |
| [Flow](#Flow) | Modo de reconhecimento total, o mecanismo tenta realizar agrupamento e análise multinível para restaurar a intenção original do autor do documento e produzir xhtml em layout fluido. |
| [PdfFlow](#PdfFlow) | A ideia principal desta conversão baseia‑se em salvar a ordem "natural" de renderização do conteúdo que é formada durante o processamento de documentos pdf. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Retorna a constante enum deste tipo com o nome especificado. |
| [values](#values--) | Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas. |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

Este modo é rápido e bom para preservar ao máximo a aparência original das páginas, mas infelizmente muitos leitores de EPUB não suportam xhtml com layout fixo

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

Modo de reconhecimento total, o mecanismo tenta realizar agrupamento e análise multinível para restaurar a intenção original do autor do documento e produzir xhtml em layout fluido.

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

A ideia principal desta conversão baseia‑se em salvar a ordem "natural" de renderização do conteúdo que é formada durante o processamento de documentos pdf.

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Retorna a constante enum deste tipo com o nome especificado.

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas.

**Returns:**
um array contendo as constantes deste tipo enum, na ordem em que são declaradas
