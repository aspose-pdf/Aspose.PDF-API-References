---
title: "split"
second_title: "Aspose.PDF для Rust через C++"
description: "Создаёт несколько новых PDF-документов, извлекая страницы из текущего PDF-документа."
type: docs
url: /ru/rust-cpp/core/split/
---

_Создаёт несколько новых PDF-документов, извлекая страницы из текущего PDF-документа._

```rust
pub fn split(&self, page_range: &str) -> Result<Vec<Self>, PdfError>
```

**Arguments**
  * **page_range** - a string specifying page ranges, e.g. `"1-2;3;4-"`

**Returns**
  * **Ok(Vec\<Self\>)** - containing the resulting split documents, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Откройте PDF-document с именем "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Создать несколько новых PDF-документов, извлекая страницы из текущего PDF-документа
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // Сохраните каждую часть после разделения как отдельный PDF-document
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```