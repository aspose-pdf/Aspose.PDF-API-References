---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: Lizenzmethode. Lizenziert die Komponente
type: docs
weight: 20
url: /de/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Lizenziert die Komponente.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | String | Kann ein vollständiger oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. Verwenden Sie eine leere Zeichenfolge, um in den Evaluierungsmodus zu wechseln. |

## Bemerkungen

Versucht, die Lizenz an den folgenden Orten zu finden:

1. Expliziter Pfad.

2. Der Ordner, der die Aspose-Komponentenassembly enthält.

3. Der Ordner, der die aufrufende Assembly des Clients enthält.

4. Der Ordner, der die Einstieg (Startup)-Assembly enthält.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

**Hinweis:** Im .NET Compact Framework versucht es, die Lizenz nur an diesen Orten zu finden:

1. Expliziter Pfad.

2. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

[Java]

2. Der Ordner, der die Aspose-Komponenten-JAR-Datei enthält.

3. Der Ordner, der die aufrufende JAR-Datei des Clients enthält.

### Siehe auch

* Klasse [License](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

Lizenziert die Komponente.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream, der die Lizenz enthält. |

## Bemerkungen

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.

### Siehe auch

* Klasse [License](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)