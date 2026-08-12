---
title: "merge_documents"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Sağlanan PDF belgelerini birleştirerek yeni bir PDF belgesi oluşturur."
type: docs
url: /tr/rust-cpp/core/merge_documents/
---

_Sağlanan PDF belgelerini birleştirerek yeni bir PDF belgesi oluşturur._

```rust
pub fn merge_documents(documents: &[&Document]) -> Result<Self, PdfError>
```

**Arguments**
  * **documents** - a slice of references to PDF-documents to merge

**Returns**
  * **Ok((Self))** - with a new PDF-document instance, if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Yeni bir PDF-document oluştur
    let pdf1 = Document::new()?;

    // "sample.pdf" adlı bir PDF-document aç
    let pdf2 = Document::open("sample.pdf")?;

    // Sağlanan PDF belgelerini birleştirerek yeni bir PDF belgesi oluştur
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```