# CAFÉLIA — Bio-Leather & Circular Fashion

Website project built with Python + Flask, using the images from the group's IPA report.

## 1. Run on your computer

Open Command Prompt / PowerShell in this folder:

```bash
python -m venv .venv
```

Windows:
```bash
.venv\Scripts\activate
```

macOS / Linux:
```bash
source .venv/bin/activate
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Run:
```bash
python app.py
```

Then open:
http://127.0.0.1:5000

## 2. Publish a public link

Recommended: Render.

1. Create a GitHub repository and upload this whole folder.
2. On Render choose **New → Web Service** and connect the repository.
3. Runtime: Python 3.
4. Build Command: `pip install -r requirements.txt`
5. Start Command: `gunicorn app:app`
6. Choose a free instance if appropriate.
7. Deploy.

Render will give the project a public `onrender.com` URL.

## 3. Important

- The website is a presentation/prototype based on the IPA report.
- Prices and technical figures are presented as project assumptions/proposals from the report.
- The site intentionally avoids unsupported claims such as "100% biodegradable".
- For a real commercial launch, replace the demo contact details and add a real domain, legal pages, payment/order backend, analytics and verified certification documents.
