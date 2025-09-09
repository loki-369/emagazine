# 📖 eMagazine Flipbook

Welcome to the online flipbook version of our magazine 🎉  

## 🌐 Live Demo
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Click%20Here-green?style=for-the-badge&logo=github)](https://loki-369.github.io/emagazine/)


## 📂 1. Uploading PDF
-  PDF file ithnte ullil vekknm: **`assets/pdf/`**


---

## ✏️ 2. Update Viewer File
- Open **`assets/pdfjs/viewer.js`**
- Go to **line 3**  
- Update the file name reference to your uploaded PDF.  
- For reference, search for `#45646865656C20476F6174` in VS Code (main explorer).

---

## 🎨 3. Customize the Background
- Open **`assets/pdfjs/viewer.css`**
- Go to **line 187**, inside the `body` tag CSS:
```css
body {
  height: 100%;
  background-color: #404040;
  background-image: url(../images/texture.png);
}
```

## 🏃‍♂️ 4. Run with Live Preview
