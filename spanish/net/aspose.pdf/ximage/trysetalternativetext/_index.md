---
title: "XImage.TrySetAlternativeText"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "Método XImage. Establece texto alternativo para un XImage en la página"
type: docs
weight: 180
url: /es/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

Establece texto alternativo para un XImage en la página.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alternativeText | Cadena | El texto alternativo a especificar. |
| página | Página | Página donde se encuentra el XImage. |

### Valor devuelto

True si alternativeText para XImage está establecido. False si alternativeText para XImage no está establecido.

## Observaciones

El método devuelve false en los siguientes casos: - El XImage no se encuentra en la página especificada. - El XImage aparece varias veces en la página con diferentes elementos estructurales, lo que hace ambiguo qué instancia debe recibir el texto alternativo.

### Ver también

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


