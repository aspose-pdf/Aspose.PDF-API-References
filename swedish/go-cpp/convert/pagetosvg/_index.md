---
title: "PageToSvg"
second_title: "Aspose.PDF för Go via C++"
description: "Konvertera och spara den angivna sidan som Svg-bild."
type: docs
url: /sv/go-cpp/convert/pagetosvg/
---

_Konvertera och spara den angivna sidan som Svg-bild._

```go
func (document *Document) PageToSvg(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageToSvg(num int32, filename string) sparar den angivna sidan som en Svg-bildfil
	err = pdf.PageToSvg(1, "sample_page1.svg")
	if err != nil {
		log.Fatal(err)
	}
}
```
