Official public release of Vin Vin's Studio v3.8.3 (Windows Desktop & Android).

- Reliable Export & Document Saving: Fixed Web/Desktop download button state sync and strict canvas/MIME validation; added dedicated primary Save button in Android's Export dialog with MediaStore orphan cleanup and lower peak RAM for multi-page PDF printing
- Strict Multi-Person Print Sheet Validation: Validates every person assigned to a print sheet before PDF, Word (.docx), or system print export on both Web/Desktop and Android instead of silently substituting another portrait
- Safe Photo Replacement & Cleaner Permissions: Decodes new photos before replacing existing portraits on Web/Desktop, removed unused Android `READ_MEDIA_IMAGES`/`READ_EXTERNAL_STORAGE` permissions for Photo Picker, restored multi-page Android print job names, and unified Liquid-Glass button styling
- CI & Release Pipeline Hardening: Prioritized GitHub Release publishing ahead of short-lived workflow artifacts with concurrency protection
