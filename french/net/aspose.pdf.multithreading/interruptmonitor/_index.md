---
title: Class InterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Multithreading.InterruptMonitor. Représente des informations sur l'interruption
type: docs
weight: 7000
url: /fr/net/aspose.pdf.multithreading/interruptmonitor/
---
## Classe InterruptMonitor

Représente des informations sur l'interruption.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | Jeton d'annulation du moniteur utilisé pour l'interruption du processus. Par défaut, chaque IInterruptMonitor génère son propre cancellationSource. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | Obtient ou définit l'instance IInterruptMonitor qui est unique pour chaque thread. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | Libère les ressources utilisées. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | Envoie une demande d'interruption des opérations. |

### Voir aussi

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)