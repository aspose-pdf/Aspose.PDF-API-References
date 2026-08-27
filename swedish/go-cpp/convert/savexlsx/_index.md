---
title: "SaveXlsX"
second_title: "Aspose.PDF för Go via C++"
description: "Konvertera och spara det tidigare öppnade PDF-dokumentet som XlsX-dokument."
type: docs
url: /sv/go-cpp/convert/savexlsx/
---

_Konvertera och spara det tidigare öppnade PDF-dokumentet som XlsX-dokument._

```go
func (document *Document) SaveXlsX(filename string) error
```

**Parameters**: 
  * **filename** - new filename

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
	// SaveXlsX(filename string) sparar tidigare öppnat PDF-dokument som XlsX-dokument med filnamn
	err = pdf.SaveXlsX("sample.xlsx")
	if err != nil {
		log.Fatal(err)
	}
}
```
