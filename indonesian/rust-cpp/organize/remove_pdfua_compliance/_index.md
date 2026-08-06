---
title: "remove_pdfua_compliance"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Hapus kepatuhan PDF/UA dari dokumen PDF."
type: docs
url: /id/rust-cpp/organize/remove_pdfua_compliance/
---

_Hapus kepatuhan PDF/UA dari dokumen PDF._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Hapus kepatuhan PDF/UA dari PDF-document
    pdf.remove_pdfua_compliance()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_remove_pdfua_compliance.pdf")?;

    Ok(())
}

```