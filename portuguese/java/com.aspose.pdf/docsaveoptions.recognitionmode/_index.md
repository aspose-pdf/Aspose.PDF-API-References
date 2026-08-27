---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "Referência da API Aspose.PDF para Java"
description: "Permite controlar como um documento PDF é convertido em um documento de processamento de texto. Use o modo RecognitionMode.Textbox quando o documento resultante não for muito pesado."
type: docs
weight: 1050
url: /pt/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

Permite controlar como um documento PDF é convertido em um documento de processamento de texto. Use o modo RecognitionMode.Textbox quando o documento resultante não for editado extensivamente. Caixas de texto são fáceis de modificar quando há pouco a fazer. Use o modo RecognitionMode.Flow quando o documento de saída precisar de edição adicional. Parágrafos e linhas de texto no modo fluxo permitem fácil modificação do texto, mas objetos de formatação não suportados ficarão com aparência pior do que no modo RecognitionMode.Textbox.

## Campos

| Campo | Descrição |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | Um modo Flow alternativo que suporta o reconhecimento de tabelas. |
| [Flow](#Flow) | Modo de reconhecimento completo, o mecanismo realiza agrupamento e análise multinível para restaurar a intenção original do autor do documento e produzir um documento maximamente editável. |
| [Textbox](#Textbox) | Este modo é rápido e bom para preservar ao máximo a aparência original do arquivo PDF, mas a editabilidade do documento resultante pode ser limitada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Retorna a constante enum deste tipo com o nome especificado. |
| [values](#values--) | Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas. |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

Um modo Flow alternativo que suporta o reconhecimento de tabelas.

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

Modo de reconhecimento completo, o mecanismo realiza agrupamento e análise multinível para restaurar a intenção original do autor do documento e produzir um documento maximamente editável.

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

Este modo é rápido e bom para preservar ao máximo a aparência original do arquivo PDF, mas a editabilidade do documento resultante pode ser limitada.

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Retorna a constante enum deste tipo com o nome especificado.

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas.

**Returns:**
um array contendo as constantes deste tipo enum, na ordem em que são declaradas
