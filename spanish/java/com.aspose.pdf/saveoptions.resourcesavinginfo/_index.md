---
title: "SaveOptions.ResourceSavingInfo"
linktitle: "SaveOptions.ResourceSavingInfo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase representa un conjunto de datos relacionados con el guardado de archivos de recursos externos que ocurre durante la conversión de PDF a otro formato (p. ej. HTML)."
type: docs
weight: 4440
url: /es/java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

Esta clase representa un conjunto de datos relacionados con el guardado de archivos de recursos externos que ocurre durante la conversión de PDF a otro formato (p. ej. HTML).

## Métodos

| Método | Descripción |
| --- | --- |
| [getContentStream](#getContentStream--) | Establecido por el convertidor. Representa el contenido binario del archivo guardado. |
| [getResourceType](#getResourceType--) | Establecido por el convertidor. Nombre de archivo supuesto que va del convertidor al código del método personalizado. Puede usarse en código personalizado para decidir cómo procesar o dónde guardar ese archivo. |
| [getSupposedFileName](#getSupposedFileName--) | Establecido por el convertidor. Nombre de archivo supuesto que va del convertidor al código del método personalizado. Puede usarse en código personalizado para decidir cómo procesar o dónde guardar ese archivo. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Esta bandera debe establecerse en "true" en el código personalizado si, por alguna razón, el archivo propuesto debe procesarse no con código personalizado sino con el propio código del convertidor de forma estándar para el convertidor. Por lo tanto, establecerla en true significa que el código personalizado no procesó el archivo referenciado y el convertidor debe manejarlo él mismo (en ambos sentidos: para guardarlo en algún lugar y para nombrarlo en el archivo de referencia). |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Esta bandera debe establecerse en "true" en el código personalizado si, por alguna razón, el archivo propuesto debe procesarse no con código personalizado sino con el propio código del convertidor de forma estándar para el convertidor. Por lo tanto, establecerla en true significa que el código personalizado no procesó el archivo referenciado y el convertidor debe manejarlo él mismo (en ambos sentidos: para guardarlo en algún lugar y para nombrarlo en el archivo de referencia). |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

Establecido por el convertidor. Representa el contenido binario del archivo guardado.

**Returns:**
matriz de bytes

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

Establecido por el convertidor. Nombre de archivo supuesto que va del convertidor al código del método personalizado. Puede usarse en código personalizado para decidir cómo procesar o dónde guardar ese archivo.

**Returns:**
elemento NodeLevelResourceType @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Establecido por el convertidor. Nombre de archivo supuesto que va del convertidor al código del método personalizado. Puede usarse en código personalizado para decidir cómo procesar o dónde guardar ese archivo.

**Returns:**
valor String

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Esta bandera debe establecerse en "true" en el código personalizado si, por alguna razón, el archivo propuesto debe procesarse no con código personalizado sino con el propio código del convertidor de forma estándar para el convertidor. Por lo tanto, establecerla en true significa que el código personalizado no procesó el archivo referenciado y el convertidor debe manejarlo él mismo (en ambos sentidos: para guardarlo en algún lugar y para nombrarlo en el archivo de referencia).

**Returns:**
valor booleano

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Esta bandera debe establecerse en "true" en el código personalizado si, por alguna razón, el archivo propuesto debe procesarse no con código personalizado sino con el propio código del convertidor de forma estándar para el convertidor. Por lo tanto, establecerla en true significa que el código personalizado no procesó el archivo referenciado y el convertidor debe manejarlo él mismo (en ambos sentidos: para guardarlo en algún lugar y para nombrarlo en el archivo de referencia).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| customProcessingCancelled |  | valor booleano |
