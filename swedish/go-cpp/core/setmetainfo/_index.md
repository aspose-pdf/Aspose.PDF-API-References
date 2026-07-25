---
title: "SetMetaInfo"
second_title: "Aspose.PDF för Go via C++"
description: "Ange metadata värde för PDF-dokument."
type: docs
url: /sv/go-cpp/core/setmetainfo/
---

_Ange metadata värde för PDF-dokument._

```go
func (document *Document) SetMetaInfo(key, value string) error
```

**Parameters**: 
  * **key** - key whose value to set
  * **value** - value to be set

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
	// SetMetaInfo(key, value string) anger metadata värde för PDF-dokument
	err = pdf.SetMetaInfo("Author", "Aspose")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_SetMetaInfo.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
