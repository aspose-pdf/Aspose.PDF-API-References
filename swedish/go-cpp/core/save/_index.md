---
title: "Save"
second_title: "Aspose.PDF för Go via C++"
description: "Spara det tidigare öppnade PDF-dokumentet."
type: docs
url: /sv/go-cpp/core/save/
---

_Spara det tidigare öppnade PDF-dokumentet._

```go
func (document *Document) Save() error
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
	// Save() sparar tidigare öppnat PDF-dokument
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
