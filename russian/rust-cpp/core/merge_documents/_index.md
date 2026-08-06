---
title: "merge_documents"
second_title: "Aspose.PDF для Rust через C++"
description: "Создаёт новый PDF-документ, объединяя предоставленные PDF-документы."
type: docs
url: /ru/rust-cpp/core/merge_documents/
---

_Создаёт новый PDF-документ, объединяя предоставленные PDF-документы._

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
    // Создайте новый PDF-документ
    let pdf1 = Document::new()?;

    // Откройте PDF-document с именем "sample.pdf"
    let pdf2 = Document::open("sample.pdf")?;

    // Создать новый PDF-документ, объединяя предоставленные PDF-документы
    let pdf_merged = Document::merge_documents(&[&pdf1, &pdf2])?;

    // Сохранить ранее открытый PDF-документ с новым именем файла
    pdf_merged.save_as("sample_merge_documents.pdf")?;

    Ok(())
}

```