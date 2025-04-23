
  [![Gemini-Generated-Image-xbo6uuxbo6uuxbo6-1.jpg](https://i.postimg.cc/L6t02LwQ/Gemini-Generated-Image-xbo6uuxbo6uuxbo6-1.jpg)](https://postimg.cc/XpvggGV9)

# RedactifyXML  ███

  

![GitHub License](https://img.shields.io/github/license/Gerald-Lofton/RedactifyXML?style=flat-square)

![GitHub Repo stars](https://img.shields.io/github/stars/Gerald-Lofton/RedactifyXML?style=flat-square)

![GitHub last commit](https://img.shields.io/github/last-commit/Gerald-Lofton/RedactifyXML?style=flat-square)

  

**RedactifyXML** is a privacy-first, fully local web app designed to scrub sensitive data from XML files. It allows you to redact personal information (e.g., names, addresses, Phone #'s, etc) with ease, providing a clear diff of changes for transparency. Built with HTML, CSS, and JavaScript, it ensures all processing happens in your browser. No data ever leaves your device.

  

---

  

## 🌟 Features

  

- **Local Processing**: All XML scrubbing happens client-side in your browser. 🔒

- **Sensitive Data Redaction**: Easily scrub tags like `firstname`, `lastname`, `ssn`, `address`, or any custom tags. 🧼

- **Diff Viewer**: See exactly what’s changed with a clear diff (e.g., **firstname**: John -> REDACTED). 📊

- **Multiple Sections**: Process multiple XML files in separate sections, with the ability to add or remove sections. 📑

- **Copy Scrubbed XML**: Copy redacted XML to your clipboard with a single click. 📋

- **Error Handling**: Detailed error messages for invalid XML, missing tags, or no matching tags. 🚨

- **Dark Mode UI**: Modern, eye-friendly design with a dark theme. 🌙

- **No Dependencies**: Runs entirely on native browser APIs—no external libraries or network calls. 🚀

  

---

  

## 🚀 Quick Start

  

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge, Safari).
  

### Installation

  

1. **Clone the Repository**:

  

```bash
git clone https://github.com/yourusername/redactifyxml.git

cd redactifyxml
```

  

2. **Run the App**:

- Open `index.html` directly in your browser, or

- Serve it using a local server for best results:

```bash

# Using Python's built-in server

python -m http.server 8000
```

Then navigate to ```http://localhost:8000```.

  

---

  

## 📖 Usage

  

### Step 1: Input XML

  

Paste your XML data into the "Input XML" textarea.

  

```xml

<customer>

<firstname>Emma</firstname>

<lastname>Watson</lastname>

<address>789 Maple Ave, Denver, CO 80203</address>

<email>emma.watson@example.com</email>

</customer>

```

### Step 2: Specify Tags to Scrub

Enter the tags you want to redact, separated by commas (e.g., `firstname, lastname, address`).

### Step 3: Scrub the XML

Click "**Scrub All XMLs**" to process the XML. The redacted XML will appear in the "Scrubbed XML" textarea.

  

### Step 4: View Diffs

  

The diff viewer shows the changes (e.g., **firstname**: Emma -> *REDACTED*).

  

### Step 5: Copy Scrubbed XML

  

Click the "**Copy**" button to copy the redacted XML to your clipboard.

  

### Step 6: Add More Sections

  

Click "**Add Another Section**" to process additional XML files. Remove sections as needed.

  

---

  

## 🔒 Privacy Guarantee

  

RedactifyXML is built with privacy as the top priority:

  

- **No Network Calls**: Your data never leaves your device.

- **No Telemetry**: No analytics, tracking, or data collection.

- **No Persistent Storage**: Data is only held in memory during your session.

- **Clipboard Awareness**: Be mindful that copied scrubbed XML may remain in your clipboard until overwritten.



## 🖼️ Screenshots

  

### Main Interface

  

[![image.png](https://i.postimg.cc/nL2fSvVD/image.png)](https://postimg.cc/678Py4vW)

  

### Diff Viewer in Action

[![image.png](https://i.postimg.cc/6q6zQvCC/image.png)](https://postimg.cc/KkVtq4qY)

  

---

  

## 🛠️ Configuration

  

- **Clipboard Permissions**: Ensure clipboard permissions are enabled in your browser for the copy feature to work (best on HTTPS or localhost).

- **Custom Tags**: You can specify any XML tag to scrub, not just PII-related ones.

## 📄 License

  

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---


Built with ❤️ and privacy in mind by **Gerald Lofton**
