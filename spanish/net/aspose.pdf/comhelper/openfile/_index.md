---
title: ComHelper.OpenFile
second_title: Aspose.PDF for .NET API Reference
description: Método ComHelper. Solo crea y devuelve un Documento usando el nombre de archivo. Lo mismo que Documento
type: docs
weight: 20
url: /es/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

Solo crea y devuelve un Documento usando *nombre de archivo*. Lo mismo que [`Document`](../../document/document/).

```csharp
public Document OpenFile(string filename)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | String | El nombre del archivo del documento pdf. |

### Valor de Retorno

Objeto Documento

### Véase También

* clase [Document](../../document/)
* clase [ComHelper](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

Inicializa y devuelve una nueva instancia de la clase [`Document`](../../document/) para trabajar con documentos encriptados.

```csharp
public Document OpenFile(string filename, string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | String | Nombre del archivo del documento. |
| password | String | Contraseña de usuario o propietario. |

### Valor de Retorno

Objeto Documento

### Véase También

* clase [Document](../../document/)
* clase [ComHelper](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

Inicializa una nueva instancia de la clase [`Document`](../../document/) para trabajar con documentos encriptados.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | String | Nombre del archivo del documento. |
| password | String | Contraseña de usuario o propietario. |
| isManagedStream | Boolean | si se establece en `true`, el flujo interno se cierra antes de salir; de lo contrario, no. |

### Valor de Retorno

Objeto Documento

### Véase También

* clase [Document](../../document/)
* clase [ComHelper](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

Abre un documento existente desde un archivo proporcionando las opciones de conversión necesarias para obtener un documento pdf.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | String | Archivo de entrada para convertir en documento pdf. |
| options | LoadOptions | Representa propiedades para convertir *nombre de archivo* en documento pdf. |

### Valor de Retorno

Objeto Documento

### Véase También

* clase [Document](../../document/)
* clase [LoadOptions](../../loadoptions/)
* clase [ComHelper](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)