---
title: "LoadOptions.ResourceLoadingResult"
linktitle: "LoadOptions.ResourceLoadingResult"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Resultado de la carga personalizada del recurso"
type: docs
weight: 2820
url: /es/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

Resultado de la carga personalizada del recurso

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | Crea una instancia del resultado de carga |

## Métodos

| Método | Descripción |
| --- | --- |
| [getData](#getData--) | Datos binarios que se cargan con un cargador personalizado - deben establecerse después de la carga |
| [getEncodingIfKnown](#getEncodingIfKnown--) | A veces la codificación del recurso se conoce después o durante la carga. En tal caso, el código personalizado puede proporcionar al convertidor ese conocimiento a través de este parámetro. Puedes dejar null en este parámetro si la codificación es desconocida o no importa. |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | A veces es imposible cargar el recurso solicitado por alguna razón. La indisponibilidad del recurso a menudo no provoca que las conversiones se bloqueen y el documento resultante puede crearse de todos modos (aunque quizá con una calidad ligeramente peor, sin imágenes, etc.). Si se produce una excepción durante la carga, simplemente captúrala y colócala en este parámetro; a veces esa información es útil para el convertidor al renderizar el resultado. |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | A veces el conocimiento del tipo MIME del recurso cargado es útil para el convertidor. Puedes proporcionar el tipo MIME (si se conoce después de la carga) en este parámetro. Por favor, deja el parámetro igual a null cuando el tipo MIME sea desconocido o no sea necesario suministrarlo. |
| [isLoadingCancelled](#isLoadingCancelled--) | A veces, por alguna razón, la carga no debe ocurrir mediante código personalizado. En tal caso, por favor establece esta bandera como True. Entonces el convertidor intentará usar el cargador de recursos interno predeterminado para obtener ese resultado (como se comporta en una situación en la que no se proporciona una estrategia personalizada). |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | A veces la codificación del recurso se conoce después o durante la carga. En tal caso, el código personalizado puede proporcionar al convertidor ese conocimiento a través de este parámetro. Puedes dejar null en este parámetro si la codificación es desconocida o no importa. |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | A veces es imposible cargar el recurso solicitado por alguna razón. |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | A veces, por alguna razón, la carga no debe ocurrir mediante código personalizado. En tal caso, por favor establece esta bandera como True. Entonces el convertidor intentará usar el cargador de recursos interno predeterminado para obtener ese resultado (como se comporta en una situación en la que no se proporciona una estrategia personalizada). |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | A veces el conocimiento del tipo MIME del recurso cargado es útil para el convertidor. Puedes proporcionar el tipo MIME (si se conoce después de la carga) en este parámetro. Por favor, deja el parámetro igual a null cuando el tipo MIME sea desconocido o no sea necesario suministrarlo. |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

Crea una instancia del resultado de carga

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos |  | El resultado de la carga personalizada debe proporcionarse siempre; puede ser una matriz de longitud cero si es imposible obtener cualquier resultado |

### getData {#getData--}
```
public byte[] getData()
```

Datos binarios que se cargan con un cargador personalizado - deben establecerse después de la carga

**Returns:**
matriz de valores de bytes

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

A veces la codificación del recurso se conoce después o durante la carga. En tal caso, el código personalizado puede proporcionar al convertidor ese conocimiento a través de este parámetro. Puedes dejar null en este parámetro si la codificación es desconocida o no importa.

**Returns:**
Instancia de Charset

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

A veces es imposible cargar el recurso solicitado por alguna razón. La indisponibilidad del recurso a menudo no provoca que las conversiones se bloqueen y el documento resultante puede crearse de todos modos (aunque quizá con una calidad ligeramente peor, sin imágenes, etc.). Si se produce una excepción durante la carga, simplemente captúrala y colócala en este parámetro; a veces esa información es útil para el convertidor al renderizar el resultado.

**Returns:**
Excepción

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

A veces el conocimiento del tipo MIME del recurso cargado es útil para el convertidor. Puedes proporcionar el tipo MIME (si se conoce después de la carga) en este parámetro. Por favor, deja el parámetro igual a null cuando el tipo MIME sea desconocido o no sea necesario suministrarlo.

**Returns:**
valor String

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

A veces, por alguna razón, la carga no debe ocurrir mediante código personalizado. En tal caso, por favor establece esta bandera como True. Entonces el convertidor intentará usar el cargador de recursos interno predeterminado para obtener ese resultado (como se comporta en una situación en la que no se proporciona una estrategia personalizada).

**Returns:**
valor booleano

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
A veces la codificación del recurso se conoce después o durante la carga. En tal caso, el código personalizado puede proporcionar al convertidor ese conocimiento a través de este parámetro. Puedes dejar null en este parámetro si la codificación es desconocida o no importa.

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
A veces es imposible cargar el recurso solicitado por alguna razón.

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

A veces, por alguna razón, la carga no debe ocurrir mediante código personalizado. En tal caso, por favor establece esta bandera como True. Entonces el convertidor intentará usar el cargador de recursos interno predeterminado para obtener ese resultado (como se comporta en una situación en la que no se proporciona una estrategia personalizada).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| loadingCancelled |  | valor booleano |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
A veces el conocimiento del tipo MIME del recurso cargado es útil para el convertidor. Puedes proporcionar el tipo MIME (si se conoce después de la carga) en este parámetro. Por favor, deja el parámetro igual a null cuando el tipo MIME sea desconocido o no sea necesario suministrarlo.
