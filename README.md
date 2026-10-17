# ossia score Custom App Template

A template repository for creating custom-branded ossia score applications with your own QML user interface.

Set your app's name, organization, identifier, description, copyright and version in the `with:` block of the packaging step in both workflows, and replace the placeholder icons in `resources/icons/` with your own: `app.png` (Linux), `app.ico` (Windows) and `app.icns` (macOS). The packaging requires all three, so that the app does not ship with ossia score's icon.

The workflows package the app from the ossia score 3.9.0 release (`release-tag` in `.github/workflows/build.yml`, `score-ref` in `.github/workflows/full-build.yml`).
