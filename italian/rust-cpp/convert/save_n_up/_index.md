---
title: "save_n_up"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Converte e salva il PDF-document precedentemente aperto come N-Up PDF-document."
type: docs
url: /it/rust-cpp/convert/save_n_up/
---

_Converte e salva il PDF-document precedentemente aperto come N-Up PDF-document._

```rust
pub fn save_n_up(&self, filename: &str, columns: i32, rows: i32) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file
  * **columns** - the number of columns
  * **rows** - the number of rows

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Converti e salva il PDF-document precedentemente aperto come N-Up PDF-document
    pdf.save_n_up("sample_n_up.pdf", 2, 2)?;

    Ok(())
}
```