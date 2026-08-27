---
title: "SaveAs"
second_title: "Aspose.PDF för Go via C++"
description: "Spara det tidigare öppnade PDF-dokumentet med ett nytt filnamn."
type: docs
url: /sv/go-cpp/core/saveas/
---

_Spara det tidigare öppnade PDF-dokumentet med ett nytt filnamn._

```go
func (document *Document) SaveAs(filename string) error
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
