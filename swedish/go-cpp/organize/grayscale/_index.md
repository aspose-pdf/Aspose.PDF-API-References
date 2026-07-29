---
title: "Gråskala"
second_title: "Aspose.PDF för Go via C++"
description: "Konvertera PDF-dokument till svartvitt."
type: docs
url: /sv/go-cpp/organize/grayscale/
---

_Konvertera PDF-dokument till svartvitt._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// Grayscale() konverterar PDF-dokument till svartvitt
	err = pdf.Grayscale()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_Grayscale.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
