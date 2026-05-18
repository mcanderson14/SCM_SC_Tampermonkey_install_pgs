# Tampermonkey Installation Guide

## Install Tampermonkey

1. Open the Tampermonkey install page:
   - https://mcanderson14.github.io/SCM_SC_Tampermonkey_install_pgs/

2. Install the extension for your browser.

3. Restart your browser if prompted.

---

# Required Browser & Tampermonkey Settings

After installing Tampermonkey, additional settings must be enabled before user scripts will function correctly.

## Step 1 — Enable Developer Mode in Chrome

Open:

```text
chrome://extensions/
```

In the top-right corner of the Extensions page:

- Enable **Developer mode**

---

## Step 2 — Open Tampermonkey Details

1. Find **Tampermonkey** in the Extensions list
2. Click **Details**

---

## Step 3 — Configure Required Settings

The following settings MUST be enabled:

### Required Settings

- ✅ Allow User Scripts = ON
- ✅ Site Access = "On all sites"
- ✅ Allow access to file URLs = ON

---

# Example Configuration

![Tampermonkey Settings](tampermonkey-settings.png)

---

# Troubleshooting

## Scripts do not run

Verify:

- Developer mode is enabled
- User Scripts are allowed
- Site Access is set to "On all sites"
- Access to file URLs is enabled

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
