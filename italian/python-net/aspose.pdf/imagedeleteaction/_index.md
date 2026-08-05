---
title: "ImageDeleteAction"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Azione eseguita sull'oggetto immagine quando l'immagine viene rimossa dalla collezione. Se l'oggetto immagine è rimosso"
type: docs
weight: 6450
url: /it/python-net/aspose.pdf/imagedeleteaction/
---

## ImageDeleteAction enumeration

Azione eseguita sull'oggetto immagine quando l'immagine viene rimossa dalla collezione. Se l'oggetto immagine è rimosso

## Members
| Nome membro | Descrizione |
| :- | :- |
| KEEP_CONTENTS | L'immagine verrà rimossa dalla collezione. Se il contenuto della pagina contiene riferimenti all'immagine, questi non verranno rimossi. Il documento potrebbe diventare non valido. |
| NONE | L'immagine verrà rimossa dalla collezione e dal contenuto della pagina, ma l'oggetto immagine non verrà eliminato. La dimensione del file non verrà ridotta. |
| FORCE_DELETE | L'immagine verrà rimossa dalla collezione e l'oggetto immagine verrà rimosso dal documento. Se esistono altri riferimenti allo stesso oggetto, il documento potrebbe essere corrotto. |
| CHECK | L'immagine verrà rimossa dalla collezione e l'oggetto immagine verrà rimosso solo se non ci sono altri riferimenti all'immagine da altre pagine. Questo potrebbe richiedere più tempo rispetto all'opzione ForceDelete. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

