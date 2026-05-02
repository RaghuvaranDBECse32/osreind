# OSRE IND Website

This repository contains the OSRE IND landing page at `osre-ind-consultancy.html`.
The contact form is configured to send email via EmailJS using frontend JavaScript only.

## Files

- `osre-ind-consultancy.html` — Main website file.
- `images/` — Asset folder for site images.

## How it works

The form submission is handled entirely in the browser with EmailJS.
No Python backend is required.

The EmailJS configuration is located in the bottom of `osre-ind-consultancy.html`:
## How to run

### Option 1: Open directly in the browser

1. Open `osre-ind-consultancy.html` in your browser.
2. The page should render and the contact form will submit through EmailJS.

### Option 2: Use a local static server (recommended)

#### VS Code Live Server

1. Install the Live Server extension.
2. Open the project folder in VS Code.
3. Right-click `osre-ind-consultancy.html` and choose **Open with Live Server**.

#### Python static server

If you want to serve the file locally, run this from the project directory:

```powershell
python -m http.server 8000
```


## Troubleshooting

- If email sending fails, open the browser console and review any EmailJS error message.
- Make sure the EmailJS template fields match your form field names.
- Confirm your EmailJS account has the service and template configured correctly.
