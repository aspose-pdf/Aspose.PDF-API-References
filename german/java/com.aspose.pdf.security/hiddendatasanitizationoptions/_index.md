---
title: "HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Konfigurationsoptionen zum Bereinigen versteckter Daten in einem Dokument bereit."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

Stellt die Konfigurationsoptionen zum Bereinigen versteckter Daten in einem Dokument bereit.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [all](#all--) | Erstellt eine neue Instanz der {@link HiddenDataSanitizationOptions} Klasse mit allen Optionen für die Bereinigung gesetzt. Dies beinhaltet das Aktivieren der Entfernung von Anmerkungen, JavaScript, Metadaten, Anhängen, Suchindex, privaten Informationen, das Flachlegen von Formularen und Ebenen, während die Option zum Konvertieren von Seiten zu Bildern deaktiviert wird. Optionale Konfigurationen wie {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) oder {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) können nach dem Erhalten der Instanz manuell geändert werden, da sie standardmäßig nicht aktiv sind. |
| [getConvertPagesToImages](#getConvertPagesToImages--) | Gibt die Option zurück, Seiten in Bilder zu konvertieren. Wenn diese Option aktiviert ist, wird die Option ImageCompressionOptions ignoriert. Die Option muss manuell aktiviert werden, wenn die {@code #All()} Methode verwendet wird und sie erforderlich ist. Die Konvertierung von Seiten in Bilder erfolgt nach dem Löschen der wichtigsten versteckten Daten, die durch andere Optionen gesteuert werden. |
| [getFlattenForms](#getFlattenForms--) | Gibt einen Wert zurück, der angibt, ob Formulare im Dokument während des Bereinigungsprozesses flachgelegt werden sollen. Das Flachlegen von Formularen wandelt interaktive Formularfelder in statischen Inhalt um, wodurch sie nicht mehr editierbar oder ausfüllbar sind. |
| [getFlattenLayers](#getFlattenLayers--) | Gibt die Option zurück, die Ebenen im PDF-Dokument flachzulegen. Wenn aktiviert, werden alle Ebenen im Dokument zu einer einzigen Ebene zusammengeführt, wodurch ihre separate Struktur entfernt wird. Diese Option ist nützlich, um Dokumente zu bereinigen, indem ihr Inhalt vereinfacht wird und sichergestellt wird, dass keine versteckten Daten in Ebenen verbleiben. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Gibt die Option zur Bildkonvertierung des Dokuments zurück. Die Option muss manuell aktiviert werden, wenn die {@code #All()} Methode verwendet wird und sie erforderlich ist. |
| [getImageDpi](#getImageDpi--) | Gibt die Option zurück, Seitenbilder während der Konvertierung aufzulösen. |
| [getRemoveAnnotations](#getRemoveAnnotations--) | Gibt einen Wert zurück, der angibt, ob Anmerkungen aus dem Dokument entfernt werden sollen. Wenn aktiviert, werden alle im Dokument vorhandenen Anmerkungen während des Bereinigungsprozesses entfernt. Redaktions-Anmerkungen werden angewendet. |
| [getRemoveAttachments](#getRemoveAttachments--) | Gibt die Option zurück, alle angehängten Dateien aus dem Dokument zu entfernen. Wenn aktiviert, wird sichergestellt, dass alle Anhänge im PDF während des Bereinigungsprozesses eliminiert werden. |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | Gibt einen Wert zurück, der angibt, ob JavaScript und zugehörige Aktionen aus dem Dokument entfernt werden sollen. Diese Option ist nützlich, um potenzielle Sicherheitslücken zu beseitigen, die durch eingebettete Skripte entstehen. |
| [getRemoveMetadata](#getRemoveMetadata--) | Gibt eine Option zurück, Metadaten aus dem Dokument zu entfernen. Wenn auf true gesetzt, werden Metadaten wie Dokumenteigenschaften und zusätzliche eingebettete Metadateninformationen während der Bereinigung entfernt. |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | Gibt einen Wert zurück, der angibt, ob der Suchindex und private Informationen aus dem Dokument entfernt werden sollen. Aktiviert die Entfernung eingebetteter Suchindizes und privater Daten, um die Sicherheit und den Datenschutz des Dokuments zu verbessern. |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | Legt die Option fest, Seiten in Bilder zu konvertieren. Wenn diese Option aktiviert ist, wird die Option ImageCompressionOptions ignoriert. Die Option muss manuell aktiviert werden, wenn die {@code #All()}-Methode verwendet wird, falls sie erforderlich ist. Die Konvertierung von Seiten in Bilder erfolgt, nachdem die Hauptversteckten Daten gelöscht wurden, die durch andere Optionen gesteuert werden. |
| [setFlattenForms](#setFlattenForms-boolean-) | Legt einen Wert fest, der angibt, ob Formulare im Dokument während des Bereinigungsprozesses flachgelegt werden sollen. Das Flachlegen von Formularen wandelt interaktive Formularfelder in statischen Inhalt um, wodurch sie nicht mehr editierbar oder ausfüllbar sind. |
| [setFlattenLayers](#setFlattenLayers-boolean-) | Legt die Option fest, die Ebenen im PDF-Dokument flachzulegen. Wenn aktiviert, werden alle Ebenen im Dokument zu einer einzigen Ebene zusammengeführt, wodurch ihre separate Struktur entfernt wird. Diese Option ist nützlich, um Dokumente zu bereinigen, indem ihr Inhalt vereinfacht wird und sichergestellt wird, dass keine versteckten Daten in den Ebenen vorhanden sind. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Legt die Bildkonvertierungsoption für das Dokument fest. Die Option muss manuell aktiviert werden, wenn die {@code #All()}-Methode verwendet wird, falls sie erforderlich ist. |
| [setImageDpi](#setImageDpi-int-) | Legt die Option fest, Seitenbilder während der Konvertierung aufzulösen. |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | Legt einen Wert fest, der angibt, ob Anmerkungen aus dem Dokument entfernt werden sollen. Wenn aktiviert, werden alle im Dokument vorhandenen Anmerkungen während des Bereinigungsprozesses entfernt. Redaktions-Anmerkungen werden angewendet. |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | Legt die Option fest, alle angehängten Dateien aus dem Dokument zu entfernen. Wenn aktiviert, wird sichergestellt, dass alle Anhänge im PDF während des Bereinigungsprozesses eliminiert werden. |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | Legt einen Wert fest, der angibt, ob JavaScript und zugehörige Aktionen aus dem Dokument entfernt werden sollen. Diese Option ist nützlich, um potenzielle Sicherheitslücken zu beseitigen, die durch eingebettete Skripte entstehen. |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | Legt eine Option fest, Metadaten aus dem Dokument zu entfernen. Wenn sie auf true gesetzt ist, werden Metadaten wie Dokumenteigenschaften und zusätzliche eingebettete Metadateninformationen während der Bereinigung entfernt. |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | Legt einen Wert fest, der angibt, ob der Suchindex und private Informationen aus dem Dokument entfernt werden sollen. Aktiviert das Entfernen eingebetteter Suchindizes und privater Daten, um die Sicherheit und den Datenschutz des Dokuments zu erhöhen. |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

Erstellt eine neue Instanz der {@link HiddenDataSanitizationOptions} Klasse mit allen Optionen für die Bereinigung gesetzt. Dies beinhaltet das Aktivieren der Entfernung von Anmerkungen, JavaScript, Metadaten, Anhängen, Suchindex, privaten Informationen, das Flachlegen von Formularen und Ebenen, während die Option zum Konvertieren von Seiten zu Bildern deaktiviert wird. Optionale Konfigurationen wie {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) oder {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) können nach dem Erhalten der Instanz manuell geändert werden, da sie standardmäßig nicht aktiv sind.

**Returns:**
Eine {@link HiddenDataSanitizationOptions}-Instanz mit allen vorab konfigurierten Bereinigungsoptionen.

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

Gibt die Option zurück, Seiten in Bilder zu konvertieren. Wenn diese Option aktiviert ist, wird die Option ImageCompressionOptions ignoriert. Die Option muss manuell aktiviert werden, wenn die {@code #All()} Methode verwendet wird und sie erforderlich ist. Die Konvertierung von Seiten in Bilder erfolgt nach dem Löschen der wichtigsten versteckten Daten, die durch andere Optionen gesteuert werden.

**Returns:**
die Option, Seiten in Bilder zu konvertieren.

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

Gibt einen Wert zurück, der angibt, ob Formulare im Dokument während des Bereinigungsprozesses flachgelegt werden sollen. Das Flachlegen von Formularen wandelt interaktive Formularfelder in statischen Inhalt um, wodurch sie nicht mehr editierbar oder ausfüllbar sind.

**Returns:**
ein Wert, der angibt, ob Formulare im Dokument während des Bereinigungsprozesses flachgelegt werden sollen.

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

Gibt die Option zurück, die Ebenen im PDF-Dokument flachzulegen. Wenn aktiviert, werden alle Ebenen im Dokument zu einer einzigen Ebene zusammengeführt, wodurch ihre separate Struktur entfernt wird. Diese Option ist nützlich, um Dokumente zu bereinigen, indem ihr Inhalt vereinfacht wird und sichergestellt wird, dass keine versteckten Daten in Ebenen verbleiben.

**Returns:**
die Option, die Ebenen im PDF-Dokument flachzulegen.

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Gibt die Option zur Bildkonvertierung des Dokuments zurück. Die Option muss manuell aktiviert werden, wenn die {@code #All()} Methode verwendet wird und sie erforderlich ist.

**Returns:**
die Bildkonvertierungsoption für das Dokument.

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

Gibt die Option zurück, Seitenbilder während der Konvertierung aufzulösen.

**Returns:**
die Option, Seitenbilder während der Konvertierung aufzulösen.

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

Gibt einen Wert zurück, der angibt, ob Anmerkungen aus dem Dokument entfernt werden sollen. Wenn aktiviert, werden alle im Dokument vorhandenen Anmerkungen während des Bereinigungsprozesses entfernt. Redaktions-Anmerkungen werden angewendet.

**Returns:**
ein Wert, der angibt, ob Anmerkungen aus dem Dokument entfernt werden sollen.

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

Gibt die Option zurück, alle angehängten Dateien aus dem Dokument zu entfernen. Wenn aktiviert, wird sichergestellt, dass alle Anhänge im PDF während des Bereinigungsprozesses eliminiert werden.

**Returns:**
die Option, alle angehängten Dateien aus dem Dokument zu entfernen.

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

Gibt einen Wert zurück, der angibt, ob JavaScript und zugehörige Aktionen aus dem Dokument entfernt werden sollen. Diese Option ist nützlich, um potenzielle Sicherheitslücken zu beseitigen, die durch eingebettete Skripte entstehen.

**Returns:**
ein Wert, der angibt, ob JavaScript und zugehörige Aktionen aus dem Dokument entfernt werden sollen.

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

Gibt eine Option zurück, Metadaten aus dem Dokument zu entfernen. Wenn auf true gesetzt, werden Metadaten wie Dokumenteigenschaften und zusätzliche eingebettete Metadateninformationen während der Bereinigung entfernt.

**Returns:**
eine Option, Metadaten aus dem Dokument zu entfernen.

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

Gibt einen Wert zurück, der angibt, ob der Suchindex und private Informationen aus dem Dokument entfernt werden sollen. Aktiviert die Entfernung eingebetteter Suchindizes und privater Daten, um die Sicherheit und den Datenschutz des Dokuments zu verbessern.

**Returns:**
ein Wert, der angibt, ob der Suchindex und private Informationen aus dem Dokument entfernt werden sollen.

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

Legt die Option fest, Seiten in Bilder zu konvertieren. Wenn diese Option aktiviert ist, wird die Option ImageCompressionOptions ignoriert. Die Option muss manuell aktiviert werden, wenn die {@code #All()}-Methode verwendet wird, falls sie erforderlich ist. Die Konvertierung von Seiten in Bilder erfolgt, nachdem die Hauptversteckten Daten gelöscht wurden, die durch andere Optionen gesteuert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | die Option, Seiten in Bilder zu konvertieren. |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

Legt einen Wert fest, der angibt, ob Formulare im Dokument während des Bereinigungsprozesses flachgelegt werden sollen. Das Flachlegen von Formularen wandelt interaktive Formularfelder in statischen Inhalt um, wodurch sie nicht mehr editierbar oder ausfüllbar sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ein Wert, der angibt, ob Formulare im Dokument während des Bereinigungsprozesses flachgelegt werden sollen. |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

Legt die Option fest, die Ebenen im PDF-Dokument flachzulegen. Wenn aktiviert, werden alle Ebenen im Dokument zu einer einzigen Ebene zusammengeführt, wodurch ihre separate Struktur entfernt wird. Diese Option ist nützlich, um Dokumente zu bereinigen, indem ihr Inhalt vereinfacht wird und sichergestellt wird, dass keine versteckten Daten in den Ebenen vorhanden sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | die Option, die Ebenen im PDF-Dokument flachzulegen. |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Legt die Bildkonvertierungsoption für das Dokument fest. Die Option muss manuell aktiviert werden, wenn die {@code #All()}-Methode verwendet wird, falls sie erforderlich ist.

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

Legt die Option fest, Seitenbilder während der Konvertierung aufzulösen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | die Option, Seitenbilder während der Konvertierung aufzulösen. |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

Legt einen Wert fest, der angibt, ob Anmerkungen aus dem Dokument entfernt werden sollen. Wenn aktiviert, werden alle im Dokument vorhandenen Anmerkungen während des Bereinigungsprozesses entfernt. Redaktions-Anmerkungen werden angewendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ein Wert, der angibt, ob Anmerkungen aus dem Dokument entfernt werden sollen. |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

Legt die Option fest, alle angehängten Dateien aus dem Dokument zu entfernen. Wenn aktiviert, wird sichergestellt, dass alle Anhänge im PDF während des Bereinigungsprozesses eliminiert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | die Option, alle angehängten Dateien aus dem Dokument zu entfernen. |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

Legt einen Wert fest, der angibt, ob JavaScript und zugehörige Aktionen aus dem Dokument entfernt werden sollen. Diese Option ist nützlich, um potenzielle Sicherheitslücken zu beseitigen, die durch eingebettete Skripte entstehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ein Wert, der angibt, ob JavaScript und zugehörige Aktionen aus dem Dokument entfernt werden sollen. |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

Legt eine Option fest, Metadaten aus dem Dokument zu entfernen. Wenn sie auf true gesetzt ist, werden Metadaten wie Dokumenteigenschaften und zusätzliche eingebettete Metadateninformationen während der Bereinigung entfernt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | eine Option, Metadaten aus dem Dokument zu entfernen. |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

Legt einen Wert fest, der angibt, ob der Suchindex und private Informationen aus dem Dokument entfernt werden sollen. Aktiviert das Entfernen eingebetteter Suchindizes und privater Daten, um die Sicherheit und den Datenschutz des Dokuments zu erhöhen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ein Wert, der angibt, ob der Suchindex und private Informationen aus dem Dokument entfernt werden sollen. |
