---
title: "remove_text_headers"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dokümandan metin başlıklarını kaldırır."
type: docs
url: /tr/rust-cpp/organize/remove_text_headers/
---

_PDF-dokümandan metin başlıklarını kaldırır._

```rust
pub fn remove_text_headers(&self) -> Result<(), PdfError>
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

    // PDF-dokümandan metin başlıklarını kaldır
    pdf.remove_text_headers()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_text_headers.pdf")?;

    Ok(())
}

```