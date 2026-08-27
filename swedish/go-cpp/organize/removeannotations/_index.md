---
title: "RemoveAnnotations"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort annotationer från PDF-dokument."
type: docs
url: /sv/go-cpp/organize/removeannotations/
---

_Ta bort annotationer från PDF-dokumentet._

```go
func (document *Document) RemoveAnnotations() error
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
	// RemoveAnnotations() tar bort annotationer från PDF-dokumentet
	err = pdf.RemoveAnnotations()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_RemoveAnnotations.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
