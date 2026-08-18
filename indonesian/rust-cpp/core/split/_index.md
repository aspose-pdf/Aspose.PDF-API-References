---
title: "split"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Membuat beberapa PDF-document baru dengan mengekstrak halaman dari PDF-document saat ini."
type: docs
url: /id/rust-cpp/core/split/
---

_Membuat beberapa PDF-document baru dengan mengekstrak halaman dari PDF-document saat ini._

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
    // Buka PDF-document bernama "sample.pdf"
    let pdf_split = Document::open("sample.pdf")?;

    // Buat beberapa PDF-document baru dengan mengekstrak halaman dari PDF-document saat ini
    let pdf_parts = pdf_split.split("1-2;3-")?;

    // Simpan setiap bagian yang dibagi sebagai PDF-document terpisah
    for (i, pdf_part) in pdf_parts.iter().enumerate() {
        let pdf_filename = format!("sample_split_part{}.pdf", i + 1);
        pdf_part.save_as(&pdf_filename)?;
    }

    Ok(())
}

```