---
title: "ComHelper"
linktitle: "ComHelper"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Proporciona métodos para clientes COM para cargar un documento en Aspose.PDF. </p> <hr> <p> Utilice la clase ComHelper para cargar un documento desde un archivo o flujo en un objeto Document."
type: docs
weight: 760
url: /es/java/com.aspose.pdf/comhelper/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ComHelper

```
public class ComHelper extends Object
```

<p> Proporciona métodos para clientes COM para cargar un documento en Aspose.PDF. </p> <hr> <p> Utilice la clase ComHelper para cargar un documento desde un archivo o flujo en un objeto Document en una aplicación COM. La clase Document proporciona un constructor predeterminado para crear un nuevo documento y también ofrece constructores sobrecargados para cargar un documento desde un archivo o flujo. Si está usando Aspose.Words desde una aplicación .NET, puede usar todos los constructores de Document directamente, pero si está usando Aspose.PDF desde una aplicación COM, solo está disponible el constructor predeterminado de Document. </p>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ComHelper](#ComHelper--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [openFile](#openFile-java.lang.String-) | Simplemente cree y devuelva Document usando {@code filename}. Lo mismo que {@code Document(Stream)}. |
| [openFile](#openFile-java.lang.String-com.aspose.pdf.LoadOptions-) | Abra un documento existente desde un archivo proporcionando las opciones de conversión necesarias para obtener un documento PDF. |
| [openFile](#openFile-java.lang.String-java.lang.String-) | Inicialice y devuelva una nueva instancia de la clase {@code Document} para trabajar con un documento encriptado. |
| [openFile](#openFile-java.lang.String-java.lang.String-boolean-) | Inicialice una nueva instancia de la clase {@code Document} para trabajar con un documento encriptado. |
| [openStream](#openStream-java.io.InputStream-) | Inicialice y devuelva una nueva instancia de Document a partir del flujo {@code input}. |
| [openStream](#openStream-java.io.InputStream-boolean-) | Inicialice y devuelva una nueva instancia de Document a partir del flujo {@code input}. |
| [openStream](#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Abra y devuelva un documento existente desde un flujo proporcionando la conversión necesaria para obtener un documento PDF. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-) | Inicialice y devuelva una nueva instancia de Document a partir del flujo {@code input}. |
| [openStream](#openStream-java.io.InputStream-java.lang.String-boolean-) | Inicialice y devuelva una nueva instancia de Document a partir del flujo {@code input}. |

### ComHelper {#ComHelper--}
```
public ComHelper()
```



### openFile {#openFile-java.lang.String-}
Simplemente cree y devuelva Document usando {@code filename}. Lo mismo que {@code Document(Stream)}.

### openFile {#openFile-java.lang.String-com.aspose.pdf.LoadOptions-}
Abra un documento existente desde un archivo proporcionando las opciones de conversión necesarias para obtener un documento PDF.

### openFile {#openFile-java.lang.String-java.lang.String-}
Inicialice y devuelva una nueva instancia de la clase {@code Document} para trabajar con un documento encriptado.

### openFile {#openFile-java.lang.String-java.lang.String-boolean-}
Inicialice una nueva instancia de la clase {@code Document} para trabajar con un documento encriptado.

### openStream {#openStream-java.io.InputStream-}
Inicialice y devuelva una nueva instancia de Document a partir del flujo {@code input}.

### openStream {#openStream-java.io.InputStream-boolean-}
Inicialice y devuelva una nueva instancia de Document a partir del flujo {@code input}.

### openStream {#openStream-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Abra y devuelva un documento existente desde un flujo proporcionando la conversión necesaria para obtener un documento PDF.

### openStream {#openStream-java.io.InputStream-java.lang.String-}
Inicialice y devuelva una nueva instancia de Document a partir del flujo {@code input}.

### openStream {#openStream-java.io.InputStream-java.lang.String-boolean-}
Inicialice y devuelva una nueva instancia de Document a partir del flujo {@code input}.
