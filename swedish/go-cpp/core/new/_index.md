---
title: "Ny"
second_title: "Aspose.PDF för Go via C++"
description: "Skapa ett nytt PDF-dokument."
type: docs
url: /sv/go-cpp/core/new/
---

_Skapa ett nytt PDF-dokument._

```go
func New() (*Document, error)
```

**Parameters**: 

**Return**:
  * **\*Document** - pointer to document
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// New skapar ett nytt PDF-dokument
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
