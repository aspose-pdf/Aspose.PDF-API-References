---
title: "Interface IInterruptMonitor"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Interface Aspose.Pdf.Multithreading.IInterruptMonitor. Représente les informations sur l'interruption"
type: docs
weight: 7130
url: /fr/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor interface

Représente les informations sur l'interruption.

```csharp
public interface IInterruptMonitor : IDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | Jeton d'annulation du moniteur utilisé pour l'interruption du processus. Par défaut, chaque IInterruptMonitor génère son propre cancellationSource |

## Méthodes

| Nom | Description |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Envoie une requête pour interrompre les opérations. |

### Voir aussi

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


