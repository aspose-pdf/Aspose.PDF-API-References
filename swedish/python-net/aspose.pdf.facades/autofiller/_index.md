---
title: "AutoFiller"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en klass för att ta emot data från en databas eller annan datakälla, fyller dem i de utformade fälten i mall‑pdf‑filen och slutligen genererar en ny pdf‑fil eller ström.<br/>             Den har två inmatningslägen för mallfil: inmatning som en ström eller en pdf‑fil.<br/>             Den har fyra typer av utmatningslägen: en sammanslagen ström, en sammanslagen fil, många små strömmar, många små filer.<br/>             Den kan ta emot bokstavlig data som finns i en System.Data.DataTable."
type: docs
weight: 20
url: /sv/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

Representerar en klass för att ta emot data från en databas eller annan datakälla, fyller dem i de utformade fälten i mall‑pdf‑filen och slutligen genererar en ny pdf‑fil eller ström.<br/>             Den har två inmatningslägen för mallfil: inmatning som en ström eller en pdf‑fil.<br/>             Den har fyra typer av utmatningslägen: en sammanslagen ström, en sammanslagen fil, många små strömmar, många små filer.<br/>             Den kan ta emot bokstavlig data som finns i en System.Data.DataTable.

AutoFiller‑typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| AutoFiller() | Initierar en ny instans av klassen AutoFiller |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| output_stream | Hämtar eller anger OutputStream. Ett av fyra utdata‑lägen. Dess klassiska användningsfall är Response.OutputStream.<br/>            Se den online‑demonstrationen. |
| output_streams | Hämtar eller anger de många Output Streams. Ett av fyra utdata‑lägen. |
| input_stream | Hämtar eller anger inmatningsmall‑strömmen. Ett av två indata‑lägen. |
| input_file_name | Hämtar eller anger inmatningsmall‑filen. Ett av två indata‑lägen. |
| output_file_name | Hämtar eller anger den stora sammanslagna utdatafilen. Ett av fyra utdata‑lägen. |
| generating_path | Hämtar eller anger den genererande sökvägen för de små pdf‑filerna om många små pdf‑filer ska genereras. Den fungerar tillsammans med en annan egenskap [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName.<br/>            Ett av fyra utdata‑lägen. |
| basic_file_name | Hämtar eller anger grundfilnamnet om många små filer ska genereras. Den genererade filen kommer att vara som \"BasicFileName0\",\"BasicFileName1\",...<br/>            Den fungerar tillsammans med en annan egenskap [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| save() | Sparar alla pdf‑filer. |
| save(dest_file) | Sparar alla pdf‑filer. |
| save(dest_stream) | Sparar alla pdf‑filer. |
| bind_pdf(src_file) | Kopplar en Pdf‑fil. |
| bind_pdf(src_stream) | Kopplar en Pdf‑fil. |
| bind_pdf(src_doc) | Kopplar ett Pdf‑dokument. |
| close() | Stänger objektet och utdata‑strömmarna. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

