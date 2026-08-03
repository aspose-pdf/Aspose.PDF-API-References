---
title: "SvgSaveOptions.TreatTargetFileNameAsDirectory"
second_title: "Aspose.PDF för .NET API‑referens"
description: "SvgSaveOptions-fält. Detta alternativ definierar om en målkatalog ska skapas om den saknas, med samma namn som den begärda utdatafilen istället för själva utdatafilen. På så sätt kommer katalogen att innehålla alla utdata‑SVG‑bilder av sidorna som beskrivs nedan. Om inga utdatafiler för sidor förutom den första skapas exakt i den begärda katalogen som huvudutdatafil, men får filnamnssuffixet _2…n som definieras av sidnumret, t.ex. om du definierar utdatafilen CAsposeTestsoutput.svg och utdata innehåller flera svg‑filer för sidorna, så kommer sidfilernas skapas också i katalogen CAsposeTests och ha namn output.svg output_2.svg output_3.svg osv."
type: docs
weight: 50
url: /sv/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## SvgSaveOptions.TreatTargetFileNameAsDirectory field

Detta alternativ definierar om en målkatalog (om den ännu saknas) ska skapas med samma namn som den begärda utdatafilen istället för själva utdatafilen. På så sätt kommer katalogen att innehålla alla SVG‑bilder för sidor (som beskrivs nedan). Om alternativet är inaktiverat kommer utdatafiler för sidor utom den första att skapas exakt i den begärda katalogen som huvudutdatafil, men med filnamnssuffixet _[2...n] som bestäms av sidnumret, t.ex. om du definierar utdatafilen "C:\AsposeTests\output.svg" och utdata innehåller flera SVG‑filer för sidor, så kommer sidfilerna också att skapas i katalogen "C:\AsposeTests\" och ha namnen 'output.svg', 'output_2.svg', 'output_3.svg' osv.

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### Se även

* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


