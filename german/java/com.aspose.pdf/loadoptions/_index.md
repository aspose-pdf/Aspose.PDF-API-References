---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Der Typ LoadOptions enthält das Abstraktionsniveau für einzelne Ladeoptionen"
type: docs
weight: 2790
url: /de/java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

Der Typ LoadOptions enthält das Abstraktionsniveau für einzelne Ladeoptionen

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | Stellt das Dateiformat dar, das {@code LoadOptions} beschreibt. |
| [getWarningHandler](#getWarningHandler--) | Rückruf, um alle erzeugten Warnungen zu behandeln. Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, wodurch der Ladevorgang beendet werden soll. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Legt fest, ob das Flag zum Deaktivieren aller Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei gesetzt oder abgerufen wird. Wenn {@code } gesetzt ist, können Vorgänge mit einer Schriftart ausgeführt werden, die durch deren Lizenz verboten sind, zum Beispiel das Einbetten einer Schriftart in ein PDF‑Dokument, selbst wenn Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Standardmäßig ist {@code } gesetzt. Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet dies, dass die Person, die das Flag setzt, die gesamte Verantwortung für mögliche Lizenz‑/Gesetzesverstöße übernimmt. Sie handelt also auf eigenes Risiko. Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie sich absolut sicher sind, dass Sie kein Urheberrecht verletzen. |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Legt fest, ob das Flag zum Deaktivieren aller Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei gesetzt oder abgerufen wird. Wenn {@code } gesetzt ist, können Vorgänge mit einer Schriftart ausgeführt werden, die durch deren Lizenz verboten sind, zum Beispiel das Einbetten einer Schriftart in ein PDF‑Dokument, selbst wenn Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Standardmäßig ist {@code } gesetzt. Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet dies, dass die Person, die das Flag setzt, die gesamte Verantwortung für mögliche Lizenz‑/Gesetzesverstöße übernimmt. Sie handelt also auf eigenes Risiko. Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie sich absolut sicher sind, dass Sie kein Urheberrecht verletzen. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Rückruf, um alle erzeugten Warnungen zu behandeln. Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, wodurch der Ladevorgang beendet werden soll. |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

Stellt das Dateiformat dar, das {@code LoadOptions} beschreibt.

**Returns:**
LoadFormat‑Element @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Rückruf, um alle erzeugten Warnungen zu behandeln. Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, wodurch der Ladevorgang beendet werden soll.

**Returns:**
IWarningCallback-Wert

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Legt fest, ob das Flag zum Deaktivieren aller Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei gesetzt oder abgerufen wird. Wenn {@code } gesetzt ist, können Vorgänge mit einer Schriftart ausgeführt werden, die durch deren Lizenz verboten sind, zum Beispiel das Einbetten einer Schriftart in ein PDF‑Dokument, selbst wenn Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Standardmäßig ist {@code } gesetzt. Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet dies, dass die Person, die das Flag setzt, die gesamte Verantwortung für mögliche Lizenz‑/Gesetzesverstöße übernimmt. Sie handelt also auf eigenes Risiko. Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie sich absolut sicher sind, dass Sie kein Urheberrecht verletzen.

**Returns:**
boolescher Wert

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Legt fest, ob das Flag zum Deaktivieren aller Lizenzbeschränkungen für alle Schriftarten beim Laden der Datei gesetzt oder abgerufen wird. Wenn {@code } gesetzt ist, können Vorgänge mit einer Schriftart ausgeführt werden, die durch deren Lizenz verboten sind, zum Beispiel das Einbetten einer Schriftart in ein PDF‑Dokument, selbst wenn Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Standardmäßig ist {@code } gesetzt. Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet dies, dass die Person, die das Flag setzt, die gesamte Verantwortung für mögliche Lizenz‑/Gesetzesverstöße übernimmt. Sie handelt also auf eigenes Risiko. Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie sich absolut sicher sind, dass Sie kein Urheberrecht verletzen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Rückruf, um alle erzeugten Warnungen zu behandeln. Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, wodurch der Ladevorgang beendet werden soll.
