---
title: DocumentDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Méthode DocumentDevice. Chaque appareil représente une opération sur le document, par exemple, nous pouvons convertir un document pdf dans un autre format
type: docs
weight: 10
url: /fr/net/aspose.pdf.devices/documentdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Chaque appareil représente une opération sur le document, par exemple, nous pouvons convertir un document pdf dans un autre format.

```csharp
public abstract void Process(Document document, int fromPage, int toPage, Stream output)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Document | Le document à traiter. |
| fromPage | Int32 | Définit la page à partir de laquelle commencer le traitement. |
| toPage | Int32 | Définit la dernière page à traiter. |
| output | Stream | Définit le flux où les résultats du traitement sont stockés. |

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, Stream) {#process_2}

Traite l'ensemble du document et enregistre les résultats dans le flux.

```csharp
public void Process(Document document, Stream output)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Document | Le document à traiter. |
| output | Stream | Définit le flux où les résultats du traitement sont stockés. |

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, string) {#process_3}

Traite l'ensemble du document et enregistre les résultats dans un fichier.

```csharp
public void Process(Document document, string outputFileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Document | Le document à traiter. |
| outputFileName | String | Définit le fichier où les résultats du traitement sont stockés. |

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)

---

## Process(Document, int, int, string) {#process_1}

Traite certaines pages du document et enregistre les résultats dans un fichier.

```csharp
public void Process(Document document, int fromPage, int toPage, string outputFileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Document | Le document à traiter. |
| fromPage | Int32 | La première page à commencer le traitement. |
| toPage | Int32 | La dernière page du traitement. |
| outputFileName | String | Définit le fichier où les résultats du traitement sont stockés. |

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* class [DocumentDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)