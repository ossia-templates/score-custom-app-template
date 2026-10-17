# ossia score Custom App Template

A template repository for creating custom-branded ossia score applications with your own QML user interface.

Replace the placeholder icons in `resources/icons/` with your own: `app.png` (Linux), `app.ico` (Windows) and `app.icns` (macOS). The packaging requires all three, so that the app does not ship with ossia score's icon.

The workflows package the app from the ossia score 3.9.0 release (`release-tag` in `.github/workflows/build.yml`, `score-ref` in `.github/workflows/full-build.yml`).
