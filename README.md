# Tampermonkey Installation Guide

## Install Tampermonkey

1. Open the Tampermonkey install page:
   - https://mcanderson14.github.io/SCM_SC_Tampermonkey_install_pgs/

2. Install the extension for your browser.

3. Restart your browser if prompted.

---

# Browser-Specific Setup Instructions

## Google Chrome

Open:

```text
chrome://extensions/
```

### Required Settings

- Enable **Developer mode**
- Open **Tampermonkey → Details**
- Set:
  - ✅ Allow User Scripts = ON
  - ✅ Site Access = On all sites
  - ✅ Allow access to file URLs = ON

---

## Microsoft Edge

Open:

```text
edge://extensions/
```

### Required Settings

- Enable **Developer mode**
- Open **Tampermonkey → Details**
- Set:
  - ✅ Allow User Scripts = ON
  - ✅ Site Access = On all sites
  - ✅ Allow access to file URLs = ON

> Microsoft Edge behaves almost identically to Chrome.

---

## Mozilla Firefox

Open:

```text
about:addons
```

### Required Settings

1. Open **Extensions**
2. Select **Tampermonkey**
3. Open **Preferences** or **Manage**

Recommended:
- Allow Tampermonkey to run on:
  - All websites
  - Private windows (if needed)
- Ensure user scripts are enabled inside Tampermonkey settings

> Firefox does not use Chrome-style "Developer mode."

> Firefox handles local file access differently, so "Allow access to file URLs" is usually not required.

---

## Opera

Open:

```text
opera://extensions
```

### Required Settings

- Enable **Developer mode**
- Open **Tampermonkey → Details**
- Set:
  - ✅ Allow User Scripts = ON
  - ✅ Site Access = On all sites
  - ✅ Allow access to file URLs = ON

> Opera is Chromium-based and behaves similarly to Chrome.

---

## Safari

### Open Safari Extension Settings

1. Open Safari
2. Go to:
   - Safari → Settings
3. Open:
   - Extensions
4. Select:
   - Tampermonkey

### Required Settings

- Enable Tampermonkey
- Allow access to:
  - All Websites
- Approve any requested permissions

> Safari may require:
> - Restarting Safari
> - Approving permissions under macOS Privacy & Security

---

# Example Chrome Configuration

The following screenshot shows the recommended Chrome configuration.

<img width="1911" height="994" alt="image" src="https://github.com/user-attachments/assets/332a31bb-31e8-491b-b837-0f24e89a37b3" />


---

# Troubleshooting

## Scripts do not run

Verify:

- Developer mode is enabled (Chromium browsers)
- User Scripts are allowed
- Site Access is set to "On all sites"
- Access to file URLs is enabled (Chromium browsers)

## Browser Compatibility

Tampermonkey supports:

- Google Chrome
- Microsoft Edge
- Firefox
- Opera
- Safari

Some browsers may use slightly different wording for extension permissions.

---

# Recommended

After setup:

- Pin the Tampermonkey extension to the toolbar
- Restart the browser
- Re-open the target application/site
- Refresh the browser tab after installing scripts
