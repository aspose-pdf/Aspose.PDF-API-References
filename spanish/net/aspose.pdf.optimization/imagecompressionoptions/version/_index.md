---
title: ImageCompressionOptions.Version
second_title: Aspose.PDF for .NET API Reference
description: Propiedad ImageCompressionOptions. Versión del algoritmo de compresión. Los valores posibles son 1. compresión estándar 2. compresión rápida mejorada que es más rápida que la estándar pero puede no ser aplicable a todas las imágenes 3. compresión estándar mixta que se aplica a imágenes que no pueden ser comprimidas por el algoritmo más rápido, esto puede dar la mejor compresión pero es más lento que el algoritmo "rápido". La versión "Rápido" no es aplicable para redimensionar imágenes (se utilizará el método estándar). Por defecto es "Estándar".
type: docs
weight: 70
url: /es/net/aspose.pdf.optimization/imagecompressionoptions/version/
---
## Propiedad ImageCompressionOptions.Version

Versión del algoritmo de compresión. Los valores posibles son: 1. compresión estándar, 2. rápida (compresión mejorada que es más rápida que la estándar pero puede no ser aplicable a todas las imágenes), 3. mixta (la compresión estándar se aplica a imágenes que no pueden ser comprimidas por el algoritmo más rápido, esto puede dar la mejor compresión pero es más lento que el algoritmo "rápido". La versión "Rápido" no es aplicable para redimensionar imágenes (se utilizará el método estándar). Por defecto es "Estándar".

```csharp
public ImageCompressionVersion Version { get; set; }
```

### Ver También

* enum [ImageCompressionVersion](../../imagecompressionversion/)
* class [ImageCompressionOptions](../)
* namespace [Aspose.Pdf.Optimization](../../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../../)