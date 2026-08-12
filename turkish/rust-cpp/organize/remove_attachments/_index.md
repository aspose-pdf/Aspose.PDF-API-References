---
title: "remove_attachments"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dokümandan ekleri kaldırır."
type: docs
url: /tr/rust-cpp/organize/remove_attachments/
---

_PDF-dokümandan ekleri kaldırır._

```rust
pub fn remove_attachments(&self) -> Result<(), PdfError>
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

    // PDF-dokümanından ekleri kaldır
    pdf.remove_attachments()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_attachments.pdf")?;

    Ok(())
}

```