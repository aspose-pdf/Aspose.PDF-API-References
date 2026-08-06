---
title: "SvgSaveOptions"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Spara alternativ för export till SVG-format"
type: docs
weight: 1460
url: /sv/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

Spara alternativ för export till SVG-format

Typen SvgSaveOptions visar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| SvgSaveOptions() | Initierar en ny instans av klassen SvgSaveOptions |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| warning_handler | Återanrop för att hantera eventuella genererade varningar. <br/>            WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. <br/>            Continue är standardåtgärden och spara‑operationen fortsätter, men användaren kan också returnera Abort, varvid spara‑operationen ska avbrytas. |
| save_format | Format för datasparning. |
| close_response | Hämtar eller anger ett booleskt värde som indikerar om Response-objektet ska stängas efter att dokumentet har sparats i svaret. |
| extract_ocr_sublayer_only | Ingen |
| try_merge_adjacent_same_background_images | Ingen |
| treat_target_file_name_as_directory | Detta alternativ definierar huruvida en målkatalog ska skapas<br/>             (om den ännu saknas) med samma namn som den begärda utdatafilen <br/>             istället för själva den begärda utdatafilen.<br/>             Så att katalogen innehåller alla utdata‑SVG‑bilder för sidor (som beskrivs nedan).<br/>               Om nej, kommer utdatafiler för sidor utom den första att skapas exakt i den begärda katalogen<br/>            som huvudutdatafil, men med filnamnssuffixet _[2...n], som<br/>             definieras av sidnumret, t.ex. om du definierar utdatafilen "C:\AsposeTests\output.svg"<br/>             och utdata kommer att innehålla flera svg‑filer för sidor,<br/>             så kommer sidfilerna också att skapas i katalogen "C:\AsposeTests\" och ha namn 'output.svg', 'output_2.svg', 'output_3.svg' etc. |
| compress_output_to_zip_archive | Anger huruvida utdata ska skapas som ett zip‑arkiv.<br/>             Se kommentaren till alternativet 'TreatTargetFileNameAsDirectory' för att se namngivningsreglerna<br/>             för svg‑filer för sidor i ett flersidigt källdokument, som också tillämpas på den zip‑paketerade uppsättningen av utdatafiler. |
| scale_to_pixels | Anger huruvida utdata‑dokumentet ska skalas från typografiska punkter till pixlar. |

### Se även

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

