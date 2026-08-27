---
title: "FileSpecification"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe che rappresenta il file incorporato."
type: docs
weight: 360
url: /it/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

Classe che rappresenta il file incorporato.

Il tipo FileSpecification espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| FileSpecification(file) | Inizializza una nuova istanza della classe FileSpecification |
| FileSpecification(stream, name) | Inizializza una nuova istanza della classe FileSpecification |
| FileSpecification(file, description) | Inizializza una nuova istanza della classe FileSpecification |
| FileSpecification(stream, name, description) | Inizializza una nuova istanza della classe FileSpecification |
| FileSpecification(file_name, annot) | Inizializza una nuova istanza della classe FileSpecification |
| FileSpecification() | Crea una nuova specifica di file vuota. |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| encoding | Ottiene o imposta il formato di codifica.<br/>            Valori possibili: Zip - il file è compresso con ZIP, <br/>            None - il file non è compresso. |
| include_contents | Se true, il contenuto del file sarà incluso nella specifica del file. |
| encrypted_payload | Ottiene il payload crittografato. |
| descrizione | Ottiene o imposta il testo associato alla specifica del file. |
| af_relationship | Relazione file associata. |
| stream_contents | Ottiene il contenuto del file come stream. <br/> Il contenuto non viene caricato in memoria, il che consente di ridurre l'utilizzo della memoria.<br/> Tuttavia questo stream non supporta il posizionamento e la proprietà Length. Se hai bisogno di queste funzionalità, utilizza la proprietà Contents invece. |
| contents | Ottiene o imposta il contenuto del file. <br/> Questa proprietà restituisce i dati caricati in memoria, il che può causare un'eccezione Out of memory per dati di grandi dimensioni.<br/> Per ridurre l'utilizzo della memoria, utilizza StreamContents. |
| params | Ottiene i parametri del file. |
| mime_type | Ottiene il sottotipo del file incorporato |
| name | Ottiene o imposta il nome della specifica del file. |
| unicode_name | Ottiene o imposta il nome Unicode della specifica del file. |
| file_system | Ottiene o imposta il nome del file system. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| get_value(key) | Ottiene il parametro specifico dell'applicazione. |
| set_value(key, value) | Imposta il parametro specifico dell'applicazione. |

### Vedi anche

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

