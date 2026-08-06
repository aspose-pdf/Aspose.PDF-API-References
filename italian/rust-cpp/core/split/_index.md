---
title: "split"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Crea più nuovi PDF-documents estraendo pagine dal PDF-document corrente."
type: docs
url: /it/rust-cpp/core/split/
---

_Crea più nuovi PDF-documents estraendo pagine dal PDF-document corrente._

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
    // Apri un PDF-document chiamato "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Crea più nuovi PDF-documents estraendo pagine dal PDF-document corrente
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // Salva ogni parte divisa come un PDF-document separato
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```