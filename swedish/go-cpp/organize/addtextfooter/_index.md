---
title: "AddTextFooter"
second_title: "Aspose.PDF för Go via C++"
description: "Lägg till text i sidfoten på ett PDF-dokument."
type: docs
url: /sv/go-cpp/organize/addtextfooter/
---

_Lägg till text i sidfot på ett PDF-dokument._

```go
func (document *Document) AddTextFooter(footer string) error
```

**Parameters**: 
  * **footer** - pages footer

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
	// AddTextFooter(footer string) lägger till text i sidfot på ett PDF-dokument
	err = pdf.AddTextFooter("Footer")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_AddTextFooter.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
