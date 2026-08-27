---
title: "PageMergeLayers"
second_title: "Aspose.PDF för Go via C++"
description: "Slå samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet."
type: docs
url: /sv/go-cpp/organize/pagemergelayers/
---

_Slå samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet._

```go
func (document *Document) PageMergeLayers(num int32, newLayerName string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **newLayerName** - name of the new layer after merging

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
	// PageMergeLayers(num int32, newLayerName string) slår samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet
	err = pdf.PageMergeLayers(1, "newLayerName")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
	err = pdf.SaveAs("sample_PageMergeLayers.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
