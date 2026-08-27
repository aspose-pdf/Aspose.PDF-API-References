---
title: "TeXLoadOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar alternativ för inläsning/import av TeX-fil i PDF-dokument."
type: docs
weight: 1520
url: /sv/python-net/aspose.pdf/texloadoptions/
---

## TeXLoadOptions class

Representerar alternativ för inläsning/import av TeX-fil i PDF-dokument.

Typen TeXLoadOptions visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| TeXLoadOptions() | Initierar en ny instans av klassen TeXLoadOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| warning_handler | Återanrop för att hantera eventuella genererade varningar. <br/>            WarningHandler returnerar ReturnAction‑enum‑värde som specificerar antingen Continue eller Abort. <br/>            Continue är standardåtgärden och Load‑operationen fortsätter, men användaren kan också returnera Abort, varvid Load‑operationen ska avbrytas. |
| load_format | Representerar filformat som [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) beskriver. |
| job_name | Hämtar/anger namnet på jobbet. |
| input_directory | Hämtar/anger TeX-indatakatalogen. |
| output_directory | Hämtar/anger TeX-utdatakatalogen. |
| upprepa | Hämtar/anger flaggan som indikerar om det är nödvändigt att köra TeX‑jobbet två gånger i vissa fall,<br/>            till exempel när det finns referenser i indata‑TeX‑fil(er). Generellt är detta beteende användbart när<br/>            motorn samlar in data under typsättningsprocessen och lagrar den i en hjälpfil,<br/>            allt under första körningen. Och vid den andra körningen använder motorn på något sätt den datan. |
| subset_fonts | Hämtar/anger flaggan som indikerar om teckensnitt ska delmängdas i utdatafilen eller inte. |
| show_terminal_output | Hämtar/anger flaggan som indikerar om terminalutdata ska visas i konsolen. |
| date_time | Hämtar/anger ett visst värde för datum/tid‑primitiver som \year, \month, \day och \time. |
| no_ligatures | Hämtar/anger en flagga som avaktiverar ligaturer i alla teckensnitt. |
| rasterize_formulas | Hämtar/anger en flagga som möjliggör rasterisering av matematiska formler. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

