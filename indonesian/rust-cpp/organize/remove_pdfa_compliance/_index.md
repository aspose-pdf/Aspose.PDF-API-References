---
title: "remove_pdfa_compliance"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Hapus kepatuhan PDF/A dari dokumen PDF."
type: docs
url: /id/rust-cpp/organize/remove_pdfa_compliance/
---

_Hapus kepatuhan PDF/A dari dokumen PDF._

```rust
pub fn remove_pdfa_compliance(&self) -> Result<(), PdfError>
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

    // Hapus kepatuhan PDF/A dari PDF-document
    pdf.remove_pdfa_compliance()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_remove_pdfa_compliance.pdf")?;

    Ok(())
}

```