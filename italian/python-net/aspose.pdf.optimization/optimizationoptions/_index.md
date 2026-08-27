---
title: "OptimizationOptions"
second_title: "Aspose.PDF per Python via .NET Riferimento API"
description: "Classe che descrive l'algoritmo di ottimizzazione del documento.<br/>            Un'istanza di questa classe può essere usata come parametro del metodo OptimizeResources()."
type: docs
weight: 20
url: /it/python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

Classe che descrive l'algoritmo di ottimizzazione del documento.<br/>            Un'istanza di questa classe può essere usata come parametro del metodo OptimizeResources().

Il tipo OptimizationOptions espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| OptimizationOptions() | Inizializza una nuova istanza della classe OptimizationOptions |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| link_duplcate_streams | Se questo flag è impostato su true, i flussi di risorse verranno analizzati. Se vengono trovati flussi duplicati (cioè se il contenuto del flusso è uguale), tali flussi verranno memorizzati come un unico oggetto. <br/>            Questo consente di ridurre la dimensione del documento in alcuni casi (ad esempio, quando lo stesso documento è stato concatenato più volte). |
| allow_reuse_page_content | Se true, i contenuti della pagina verranno riutilizzati quando il documento è ottimizzato per pagine uguali. |
| remove_unused_streams | Se questo flag è impostato su true, ogni risorsa viene controllata per il suo utilizzo. Se una risorsa non è mai utilizzata, viene rimossa.<br/>            Questo può ridurre la dimensione del documento, ad esempio quando le pagine sono state estratte dal documento. |
| remove_unused_objects | Se questo flag è impostato su true, tutti gli oggetti del documento verranno controllati e gli oggetti inutilizzati (cioè oggetti che non hanno alcun riferimento) vengono rimossi dal documento. |
| image_compression_options | Insieme di opzioni che descrivono se le immagini nel documento saranno compresse e i parametri della compressione. |
| compress_images | Se questo flag è impostato su true, le immagini saranno compresse nel documento. Il livello di compressione è specificato con la proprietà ImageQuality. |
| resize_images | Se questo flag è impostato su true e CompressImages è true, le immagini saranno ridimensionate se la risoluzione dell'immagine è maggiore del parametro MaxResolution specificato. |
| image_quality | Specifica il livello di compressione dell'immagine quando viene utilizzato il flag CompressIamges. |
| max_resoultion | Specifica la risoluzione massima delle immagini. Se l'immagine ha una risoluzione più alta, verrà ridimensionata. |
| unembed_fonts | Rende i caratteri non incorporati se impostato su true. |
| subset_fonts | I caratteri saranno convertiti in sottoinsiemi se impostato su true. |
| remove_private_info | Rimuove le informazioni private (informazioni sulla pagina). |
| image_encoding | Codifica immagine che verrà utilizzata. |
## Metodi
| Nome | Descrizione |
| :- | :- |
| all() | Crea una strategia di ottimizzazione con tutte le opzioni attivate.<br/>            Si prega di notare che vengono attivate solo le opzioni che non modificano alcuna funzionalità del documento.<br/>            Ad esempio, la compressione delle immagini e la rimozione dell'incorporamento dei caratteri non saranno abilitate (e possono essere incorporate manualmente). |

### Vedi anche

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

