---
title: "RemoveJavaScripts"
second_title: "Aspose.PDF för Go via C++"
description: "Ta bort Java-skript från PDF-dokument."
type: docs
url: /sv/go-cpp/organize/removejavascripts/
---

_Ta bort JavaScript från PDF-dokumentet._

```go
func (document *Document) RemoveJavaScripts() error
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
	// RemoveJavaScripts() tar bort JavaScript från PDF-dokumentet
	err = pdf.RemoveJavaScripts()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_RemoveJavaScripts.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
