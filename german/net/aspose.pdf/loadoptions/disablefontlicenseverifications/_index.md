---
title: LoadOptions.DisableFontLicenseVerifications
second_title: Aspose.PDF for .NET API Reference
description: LoadOptions-Eigenschaft. Ruft ein Flag ab oder legt es fest, um alle Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn wahr, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel erlaubt es, eine Schriftart in ein PDF-Dokument einzubetten, auch wenn die Lizenzregeln das Einbetten dieser Schriftart deaktivieren. Standardmäßig falsch
type: docs
weight: 10
url: /de/net/aspose.pdf/loadoptions/disablefontlicenseverifications/
---
## LoadOptions.DisableFontLicenseVerifications-Eigenschaft

Ruft ein Flag ab oder legt es fest, um alle Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei zu deaktivieren. Wenn `true`, erlaubt es, Operationen mit Schriftarten auszuführen, die durch eine Lizenz dieser Schriftart verboten sind, zum Beispiel erlaubt es, eine Schriftart in ein PDF-Dokument einzubetten, auch wenn die Lizenzregeln das Einbetten dieser Schriftart deaktivieren. Standardmäßig `false`.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

## Hinweise

Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet das, dass die Person, die dieses Flag setzt, die gesamte Verantwortung für mögliche Lizenz-/Gesetzesverstöße selbst übernimmt. Daher geschieht dies auf eigenes Risiko. Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie sich vollkommen sicher sind, dass Sie das Urheberrecht nicht verletzen.

### Siehe auch

* Klasse [LoadOptions](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)