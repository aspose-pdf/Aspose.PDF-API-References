---
title: "remove_attachments"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus lampiran dari dokumen PDF."
type: docs
url: /id/rust-cpp/organize/remove_attachments/
---

_Menghapus lampiran dari dokumen PDF._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Hapus lampiran dari PDF-document
    pdf.remove_attachments()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_remove_attachments.pdf")?;

    Ok(())
}

```