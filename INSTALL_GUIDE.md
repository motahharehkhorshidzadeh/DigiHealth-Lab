# Install guide

This app is a PWA. It cannot be installed from a downloaded `file://` URL. Host the whole folder on HTTPS first, then open the HTTPS link on the mobile device.

Android: open the HTTPS link in Chrome → tap Install if prompted, or Chrome menu → Install app / Add to Home screen.

iPhone/iPad: open the HTTPS link in Safari → Share → Add to Home Screen → Add.

For quick desktop testing run:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.
