---
title: "Split"
second_title: "Aspose.PDF för Go via C++"
description: "Skapa flera nya PDF-dokument genom att extrahera sidor från det aktuella PDF-dokumentet."
type: docs
url: /sv/go-cpp/core/split/
---

_Skapa flera nya PDF-dokument genom att extrahera sidor från det aktuella PDF-dokumentet._

```go
func (document *Document) Split(pagerange string) ([]*Document, error)
```

**Parameters**: 
  * **pagerange** - string that defines how to split the PDF-document. Each segment, separated by `;`, specifies the page range for a separate output PDF document. The page range syntax supports individual pages, ranges, and open-ended intervals. For example: "1,3,5;7-10", "-3;4-", or "1;2-3;5-"

**Return**: 
  * **[]\*Document** - slice of new PDF-documents, each containing the pages defined by a corresponding segment of the specified page range
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import (
	"fmt"
	"github.com/aspose-pdf/aspose-pdf-go-cpp"
	"log"
)

func main() {
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf_split, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf_split.Close()

	// Split(pagerange string) skapar flera nya PDF-dokument genom att extrahera sidor från det aktuella PDF-dokumentet
	pdfs, err := pdf_split.Split("1-2;3;4-")
	if err != nil {
		log.Fatal(err)
	}

	// Spara varje delad PDF-dokument som en separat fil
	for i, pdf := range pdfs {
		defer pdf.Close()
		filename := fmt.Sprintf("sample_Split_part%d.pdf", i+1)
		// SaveAs(filename string) sparar tidigare öppnat PDF-dokument med ett nytt filnamn
		err := pdf.SaveAs(filename)
		if err != nil {
			log.Fatal(err)
		}
	}
}
```
