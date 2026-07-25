---
title: "Graustufen"
second_title: "Aspose.PDF für Go über C++"
description: "PDF-Dokument in Schwarzweiß konvertieren."
type: docs
url: /de/go-cpp/organize/grayscale/
---

_Konvertiert PDF-Dokument zu Schwarz‑weiß._

```go
func (document *Document) Grayscale() error
```

**Parameters**: 

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// Grayscale() konvertiert PDF-Dokument zu Schwarz‑weiß
	err = pdf.Grayscale()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_Grayscale.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
