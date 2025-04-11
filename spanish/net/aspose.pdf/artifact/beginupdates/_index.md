---
title: Artifact.BeginUpdates
second_title: Aspose.PDF for .NET API Reference
description: Método Artifact. Iniciar actualizaciones retrasadas. Utilice esta función si necesita realizar varios cambios en el mismo artefacto para mejorar el rendimiento. Por lo general, los operadores de artefactos se cambian cada vez que se cambia una propiedad del artefacto. Esto provoca un cambio en el contenido de la página cada vez que se cambia el artefacto. Para evitar este efecto, coloque todas las actualizaciones del artefacto entre las llamadas a StartUpdates/SaveUpdates. Esto permite cambiar el contenido de la página solo una vez.
type: docs
weight: 230
url: /es/net/aspose.pdf/artifact/beginupdates/
---
## Método Artifact.BeginUpdates

Iniciar actualizaciones retrasadas. Utilice esta función si necesita realizar varios cambios en el mismo artefacto para mejorar el rendimiento. Por lo general, los operadores de artefactos se cambian cada vez que se cambia una propiedad del artefacto. Esto provoca un cambio en el contenido de la página cada vez que se cambia el artefacto. Para evitar este efecto, coloque todas las actualizaciones del artefacto entre las llamadas a StartUpdates/SaveUpdates. Esto permite cambiar el contenido de la página solo una vez.

```csharp
public void BeginUpdates()
```

## Ejemplos

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### Véase también

* clase [Artifact](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)