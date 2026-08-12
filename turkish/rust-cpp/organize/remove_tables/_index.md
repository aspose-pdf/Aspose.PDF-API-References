---
title: "remove_tables"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-document'ten tabloları kaldırır."
type: docs
url: /tr/rust-cpp/organize/remove_tables/
---

_PDF-document'ten tabloları kaldırır._

```rust
pub fn remove_tables(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-document'ten tabloları kaldır
    pdf.remove_tables()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_tables.pdf")?;

    Ok(())
}

```