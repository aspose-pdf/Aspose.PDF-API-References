---
title: "SaveEpub"
second_title: "Aspose.PDF för Go via C++"
description: "Konvertera och spara det tidigare öppnade PDF-dokumentet som Epub-dokument."
type: docs
url: /sv/go-cpp/convert/saveepub/
---

_Konvertera och spara det tidigare öppnade PDF-dokumentet som Epub-dokument._

```go
func (document *Document) SaveEpub(filename string) error
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
	// SaveEpub(filename string) sparar tidigare öppnat PDF-dokument som Epub-dokument med filnamn
	err = pdf.SaveEpub("sample.epub")
	if err != nil {
		log.Fatal(err)
	}
}
```
