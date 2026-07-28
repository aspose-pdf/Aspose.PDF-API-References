---
title: "FileParams"
linktitle: "FileParams"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Define un diccionario de parámetros de archivo incrustado que debe contener información adicional específica del archivo."
type: docs
weight: 1490
url: /es/java/com.aspose.pdf/fileparams/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileParams

```
public final class FileParams extends Object
```

Define un diccionario de parámetros de archivo incrustado que debe contener información adicional específica del archivo.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FileParams](#FileParams-com.aspose.pdf.FileSpecification-) | Constructor de la clase FileParams. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getCheckSum](#getCheckSum--) | Una cadena de 16 bytes que es la suma de verificación de los bytes del archivo incrustado sin comprimir. La suma de verificación se calcula aplicando el algoritmo estándar de resumen de mensaje MD5 a los bytes del flujo del archivo incrustado. |
| [getCreationDate](#getCreationDate--) | Obtiene la fecha y hora en que se creó el archivo incrustado. |
| [getModDate](#getModDate--) | Obtiene la fecha y hora en que el archivo incrustado fue modificado por última vez. |
| [getSize](#getSize--) | El tamaño del archivo incrustado sin comprimir, en bytes. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Establece la fecha y hora en que se creó el archivo incrustado. |
| [setModDate](#setModDate-java.util.Date-) | Establece la fecha y hora en que el archivo incrustado fue modificado por última vez. |

### FileParams {#FileParams-com.aspose.pdf.FileSpecification-}
Constructor de la clase FileParams.

### getCheckSum {#getCheckSum--}
```
public String getCheckSum()
```

Una cadena de 16 bytes que es la suma de verificación de los bytes del archivo incrustado sin comprimir. La suma de verificación se calcula aplicando el algoritmo estándar de resumen de mensaje MD5 a los bytes del flujo del archivo incrustado.

**Returns:**
valor String

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Obtiene la fecha y hora en que se creó el archivo incrustado.

**Returns:**
Objeto Date

### getModDate {#getModDate--}
```
public Date getModDate()
```

Obtiene la fecha y hora en que el archivo incrustado fue modificado por última vez.

**Returns:**
Objeto Date

### getSize {#getSize--}
```
public int getSize()
```

El tamaño del archivo incrustado sin comprimir, en bytes.

**Returns:**
valor int

### setCreationDate {#setCreationDate-java.util.Date-}
Establece la fecha y hora en que se creó el archivo incrustado.

### setModDate {#setModDate-java.util.Date-}
Establece la fecha y hora en que el archivo incrustado fue modificado por última vez.
