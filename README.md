# Banglaphone

Learn Roman diacritics (ISO 15919 style) for Bengali phonemes.
Learn tiles, memory-match game, and a writing pad with live Bengali preview.

## Build the APK on GitHub
1. Create a repo and push this folder to `main`.
2. Actions tab -> "Build Android APK" -> Run workflow (or push to main).
3. Download artifact `banglaphone-debug-apk`, unzip, install `app-debug.apk`.

CLI:
    gh workflow run build-apk.yml
    # or publish a Release with the APK attached:
    git tag v1.0.0 && git push origin v1.0.0
    gh run watch
    gh run download -n banglaphone-debug-apk

## Test in a browser
Open `www/index.html` directly.
