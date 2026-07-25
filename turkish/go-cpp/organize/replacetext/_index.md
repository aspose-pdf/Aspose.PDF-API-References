---
title: "ReplaceText"
second_title: "Aspose.PDF for Go via C++"
description: "PDF belgesindeki metni değiştir."
type: docs
url: /tr/go-cpp/organize/replacetext/
---

_PDF-belgede metni değiştir._

```go
func (document *Document) ReplaceText(findText, replaceText string) error
```

**Parameters**: 
  * **findText** - text fragment to search
  * **replaceText** - text fragment to replace

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// ReplaceText(findText, replaceText string) PDF-belgedeki metni değiştirir
	err = pdf.ReplaceText("PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
