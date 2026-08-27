---
title: "PageSetSize"
second_title: "Aspose.PDF für Go über C++"
description: "Seitengröße festlegen."
type: docs
url: /de/go-cpp/organize/pagesetsize/
---

_Setze die Größe der Seite._

```go
func (document *Document) PageSetSize(num int32, pageSize int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **pageSize** - page size:
```go
const (
    PageSizeA0         int32 = 0  // A0 size.
    PageSizeA1         int32 = 1  // A1 size.
    PageSizeA2         int32 = 2  // A2 size.
    PageSizeA3         int32 = 3  // A3 size.
    PageSizeA4         int32 = 4  // A4 size.
    PageSizeA5         int32 = 5  // A5 size.
    PageSizeA6         int32 = 6  // A6 size.
    PageSizeB5         int32 = 7  // B5 size.
    PageSizePageLetter int32 = 8  // PageLetter size.
    PageSizePageLegal  int32 = 9  // PageLegal size.
    PageSizePageLedger int32 = 10 // PageLedger size.
    PageSizeP11x17     int32 = 11 // P11x17 size.
)
```

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
	// PageSetSize(num int32, pageSize int32) setzt die Größe der Seite
	err = pdf.PageSetSize(1, asposepdf.PageSizeA1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) speichert das zuvor geöffnete PDF-Dokument mit neuem Dateinamen
	err = pdf.SaveAs("sample_page1_SetSize_A1.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
