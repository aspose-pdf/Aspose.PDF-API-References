---
title: "SaveDocXEnhanced"
second_title: "Aspose.PDF для Go через C++"
description: "Преобразовать и сохранить ранее открытый PDF-документ как DocX-документ с расширенным режимом распознавания (полностью редактируемые таблицы и абзацы)."
type: docs
url: /ru/go-cpp/convert/savedocxenhanced/
---

_Преобразовать и сохранить ранее открытый PDF-документ как DocX-документ с режимом расширенного распознавания (полностью редактируемые таблицы и абзацы)._

```go
func (document *Document) SaveDocXEnhanced(filename string) error
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
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// SaveDocX(filename string) сохраняет ранее открытый PDF-документ как DocX-документ в режиме расширенного распознавания с именем файла
	err = pdf.SaveDocXEnhanced("sampleEnhanced.docx")
	if err != nil {
		log.Fatal(err)
	}
}
```
