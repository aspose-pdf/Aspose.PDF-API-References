---
title: "HtmlSaveOptions.FontEncodingRules"
linktitle: "HtmlSaveOptions.FontEncodingRules"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta enumeración define reglas que afinan la lógica de codificación"
type: docs
weight: 2050
url: /es/java/com.aspose.pdf/htmlsaveoptions.fontencodingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.FontEncodingRules

```
public static final class HtmlSaveOptions.FontEncodingRules extends com.aspose.ms.System.Enum
```

Esta enumeración define reglas que afinan la lógica de codificación

## Campos

| Campo | Descripción |
| --- | --- |
| [DecreaseToUnicodePriorityLevel](#DecreaseToUnicodePriorityLevel) | ToUnicode es un mecanismo especial que ayuda a decodificar códigos de entrada a símbolos unicode. Según la especificación, debe ser utilizado como el primer mecanismo para obtener símbolos unicode para un código de entrada específico. Pero algunos documentos tienen fuentes no estándar y, para convertir estos documentos correctamente, puede ser necesario disminuir la prioridad de ToUnicode y usar otros mecanismos para decodificar los códigos de entrada. |
| [Default](#Default) | Dejar la lógica de codificación "as is" - de acuerdo con la especificación PDF |

### DecreaseToUnicodePriorityLevel {#DecreaseToUnicodePriorityLevel}
```
public static final byte DecreaseToUnicodePriorityLevel
```

ToUnicode es un mecanismo especial que ayuda a decodificar códigos de entrada a símbolos unicode. Según la especificación, debe ser utilizado como el primer mecanismo para obtener símbolos unicode para un código de entrada específico. Pero algunos documentos tienen fuentes no estándar y, para convertir estos documentos correctamente, puede ser necesario disminuir la prioridad de ToUnicode y usar otros mecanismos para decodificar los códigos de entrada.

### Default {#Default}
```
public static final byte Default
```

Dejar la lógica de codificación "as is" - de acuerdo con la especificación PDF
