---
title: "split"
second_title: "Aspose.PDF para Rust vía C++"
description: "Crea varios PDF-documents nuevos extrayendo páginas del PDF-document actual."
type: docs
url: /es/rust-cpp/core/split/
---

_Crea varios PDF-documents nuevos extrayendo páginas del PDF-document actual._

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
    // Abrir un PDF-documento llamado "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Crear varios PDF-documents nuevos extrayendo páginas del PDF-document actual
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // Guardar cada parte dividida como un PDF-documento separado
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```