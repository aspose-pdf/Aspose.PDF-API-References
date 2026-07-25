---
title: "ReplaceText"
second_title: "Aspose.PDF для Go через C++"
description: "Заменить текст в PDF-документе."
type: docs
url: /ru/go-cpp/organize/replacetext/
---

_Заменить текст в PDF‑документе._

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
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// ReplaceText(findText, replaceText string) заменяет текст в PDF‑документе
	err = pdf.ReplaceText("PDF", "TXT")
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_ReplaceText.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
