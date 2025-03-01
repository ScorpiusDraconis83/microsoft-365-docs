---
title: Overview of optical character recognition in Microsoft Syntex (Preview)
ms.author: chucked
author: chuckedmonson
manager: pamgreen
ms.reviewer: kkameth
ms.date: 10/03/2023
audience: admin
ms.topic: conceptual
ms.service: microsoft-syntex
ms.custom: admindeeplinkMAC
search.appverid: 
ms.collection: 
    - enabler-strategic
    - m365initiative-syntex
ms.localizationpriority: medium
description: Learn about optical character recognition in Microsoft Syntex.
---

# Overview of optical character recognition in Microsoft Syntex (Preview)

The optical character recognition (OCR) service in Microsoft Syntex lets you extract printed or handwritten text from images, such as posters, drawings, and product labels, as well as from documents like articles, reports, forms, and invoices.

The text is typically extracted as words, text lines, and paragraphs or text blocks, enabling access to digital version of the scanned text. The extracted information is indexed in search and can be made available for compliance features like [data loss prevention (DLP)](../compliance/dlp-learn-about-dlp.md).

For example, you enable the OCR service and then add image files to your document library. Syntex automatically scans the image files, extracts the relevant text, and makes the text from the images available for search and indexing. This lets you quickly and accurately find the keywords and phrases you're looking for.

## Requirements and limitations

### Supported file types

|Endpoint  |Supported file types  |
|---------|---------|
|SharePoint and OneDrive     |.bmp, .png, .jpeg, .jpg, .jfif, .arw, .cr2, .crw, .erf, .gif, .mef, .mrw, .nef, .nrw, .orf, .pef, .raw, .rw2, .rw1, .sr2, .tif, .tiff, .heic, .heif, .ari, .bay, .cap, .cr3, .dcs, .dcr, .drf, .eip, .fff, .iiq, .k25, .kdc, .mef, .mos, .ptx, .pxn, .raf, .rwl, .sr2, .srf, .srw, .x3f, .dng, .tiff, and .pdf (image only)  |
|Teams, Exchange, and Windows devices     |.bmp, .png, .jpeg, .jpg, .tiff, and .pdf (image only)     |

### Supported languages

The OCR service supports more than [150 languages](/azure/cognitive-services/language-support).

### Supported locations and solutions

The OCR service supports multiple solutions, as shown in the following table. For details about compliance solutions, see [Supported locations and solutions in Microsoft Purview](/purview/ocr-learn-about#supported-locations-and-solutions).

|Location    |Supported solution  |
|---------|---------|
|Exchange           |Text is available for end-user search and search-driven solutions.<br>Text is available for [compliance solutions](/purview/ocr-learn-about#supported-locations-and-solutions). |
|SharePoint sites   |Text is available for end-user search and search-driven solutions.<br>Text is available for [compliance solutions](/en-us/purview/ocr-learn-about#supported-locations-and-solutions). |
|OneDrive accounts  |Text is available for end-user search and search-driven solutions.<br>Text is available for [compliance solutions](/purview/ocr-learn-about#supported-locations-and-solutions). |
|Teams chat and channel message  |Text is available for [compliance solutions](/purview/ocr-learn-about#supported-locations-and-solutions). |
|Devices            | Text is available for [compliance solutions](/purview/ocr-learn-about#supported-locations-and-solutions).    |

### File limitations

- Image file sizes must be less than 50 MB.

- Images must be at least 50 x 50 pixels and not larger than 16,000 x 16,000 pixels.

- Only images uploaded after OCR has been enabled are scanned.

- Currently, images that are embedded in Office documents aren't supported.

