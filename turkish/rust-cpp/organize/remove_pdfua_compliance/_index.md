---
title: "remove_pdfua_compliance"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümandan PDF/UA uyumluluğunu kaldır."
type: docs
url: /tr/rust-cpp/organize/remove_pdfua_compliance/
---

_PDF-dökümandan PDF/UA uyumluluğunu kaldır._

```rust
pub fn remove_pdfua_compliance(&self) -> Result<(), PdfError>
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

    // Bir PDF-document'ten PDF/UA uyumluluğunu kaldır
    pdf.remove_pdfua_compliance()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_pdfua_compliance.pdf")?;

    Ok(())
}

```