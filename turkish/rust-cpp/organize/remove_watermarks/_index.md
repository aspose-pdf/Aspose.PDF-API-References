---
title: "remove_watermarks"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dokümandan filigranları kaldırır."
type: docs
url: /tr/rust-cpp/organize/remove_watermarks/
---

_PDF-dokümandan filigranları kaldırır._

```rust
pub fn remove_watermarks(&self) -> Result<(), PdfError>
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

    // PDF-dokümandan filigranları kaldır
    pdf.remove_watermarks()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_watermarks.pdf")?;

    Ok(())
}

```