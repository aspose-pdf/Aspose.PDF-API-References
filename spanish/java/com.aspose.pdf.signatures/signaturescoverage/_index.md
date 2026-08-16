---
title: "SignaturesCoverage"
linktitle: "SignaturesCoverage"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un enum para el nivel de cobertura proporcionado por las firmas digitales en un documento."
type: docs
weight: 40
url: /es/java/com.aspose.pdf.signatures/signaturescoverage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.signatures.SignaturesCoverage, com.aspose.ms.System.Enum, com.aspose.pdf.signatures.SignaturesCoverage

```
public final class SignaturesCoverage extends com.aspose.ms.System.Enum
```

Representa un enum para el nivel de cobertura proporcionado por las firmas digitales en un documento.

## Campos

| Campo | Descripción |
| --- | --- |
| [EntirelySigned](#EntirelySigned) | Indica que el documento está completamente cubierto por firmas digitales. Este valor significa que todas las partes requeridas del documento han sido firmadas y ninguna firma está comprometida. |
| [PartiallySigned](#PartiallySigned) | Indica que el documento está parcialmente firmado, lo que significa que parte, pero no todo, de su contenido está cubierto por firmas digitales. Este valor se usa cuando ciertas partes del documento permanecen sin firmar o están excluidas de la cobertura de firmas. |
| [Undefined](#Undefined) | Indica que el estado de la cobertura de firmas digitales en el documento es indefinido. Este valor se utiliza típicamente cuando una o más firmas en el documento están comprometidas o no pueden verificarse, impidiendo una evaluación definitiva de la cobertura de firmas del documento. |

### EntirelySigned {#EntirelySigned}
```
public static final int EntirelySigned
```

Indica que el documento está completamente cubierto por firmas digitales. Este valor significa que todas las partes requeridas del documento han sido firmadas y ninguna firma está comprometida.

### PartiallySigned {#PartiallySigned}
```
public static final int PartiallySigned
```

Indica que el documento está parcialmente firmado, lo que significa que parte, pero no todo, de su contenido está cubierto por firmas digitales. Este valor se usa cuando ciertas partes del documento permanecen sin firmar o están excluidas de la cobertura de firmas.

### Undefined {#Undefined}
```
public static final int Undefined
```

Indica que el estado de la cobertura de firmas digitales en el documento es indefinido. Este valor se utiliza típicamente cuando una o más firmas en el documento están comprometidas o no pueden verificarse, impidiendo una evaluación definitiva de la cobertura de firmas del documento.
