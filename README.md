# Transformer CSV → KML Converter

Web/PWA + Android app for converting transformer survey CSV files into KML.

## Transformer name rule
`PoleNumber_EquipmentType_EquipmentUse`

`EquipmentUse` (raw Column O) is preferred over the old Remarks/Column U value.

## Web
Open `index.html` or deploy the repository to Netlify/GitHub Pages.

## Android APK
The workflow `.github/workflows/build-apk.yml` builds a debug APK automatically on every push to `main` and can also be run manually.

Download it from: **GitHub → Actions → Build Android APK → Artifacts → TransformerKML-debug-apk**.
