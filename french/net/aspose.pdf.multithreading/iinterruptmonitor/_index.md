---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Interface Aspose.Pdf.Multithreading.IInterruptMonitor. Représente des informations sur l'interruption
type: docs
weight: 6990
url: /fr/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## Interface IInterruptMonitor

Représente des informations sur l'interruption.

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
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | Envoie une demande d'interruption des opérations. |

### Voir aussi

* espace de noms [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)