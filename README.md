# KaTeX Real-time Math Editor

## ✨ Overview

This project is a clean, single-file, browser-based application designed to make creating, customizing, and exporting high-quality mathematical equations effortless. Utilizing the speed of  KaTeX for rendering and the flexibility of modern web standards, it allows users to type LaTeX code and instantly see the result, fine-tune its appearance, and download a presentation-ready PNG image.

The single-file structure (`index.html`) makes it incredibly easy to host, share, or embed.

## 🚀 Key Features

- Real-time Rendering: Instantaneous preview of LaTeX input as KaTeX-rendered math.
- High-Resolution PNG Download: Uses `html2canvas` to capture the equation at a high scale, ensuring crystal-clear, scalable image exports with a transparent background.
- Customization Controls: Adjust the equation's appearance on the fly:
    - Font Size: Control the scale of the rendered math.
    - Text Color: Use a built-in color picker to set a precise color.
    - Background Color: Customize the background (or keep it transparent for download).
    - Delimiters: Easily wrap the LaTeX code with common delimiters like `$$...$$` or `\(...\)` for quick copying.
- Copy to Clipboard: One-click copy of the raw LaTeX code (with selected delimiters) to the clipboard.
- Built-in Library & Search: Quickly find and insert common LaTeX symbols and commands.

## 🛠️ Local Setup and Usage

Since this project is a self-contained HTML file with CDN dependencies, getting started is straightforward.

**Prerequisites**

You only need a modern web browser (Chrome, Firefox, Edge, Safari).

**Running Locally**

1. Clone the repository:

```bash
git clone [https://github.com/](https://github.com/)[Your-Username]/katex-png-equation-editor.git
cd katex-png-equation-editor
```

2. Open the file:
Simply open the index.html file in your preferred web browser.

The application will load instantly, and you can begin typing your LaTeX code!

**Image Download Fix (Troubleshooting)**

This application addresses known issues with html2canvas capturing specific large KaTeX elements (like matrix brackets or fraction lines). If you encounter rendering bugs in the downloaded image, please refer to the image download logic within the <script> tag of index.html for advanced CSS workarounds.

## 💻 Technologies Used

| Technology         | Purpose                                                                   |
|--------------------|---------------------------------------------------------------------------|
| KaTeX              | Fast math typesetting engine for real-time rendering.                     |
| html2canvas        | Captures the rendered HTML element as a high-resolution Canvas/PNG image. |
| Tailwind CSS       | Utility-first CSS framework for a responsive and modern user interface.   |
| Coloris            | Lightweight, dependency-free color picker utility.                        |
| Vanilla JavaScript | Core application logic, DOM manipulation, and file handling.              |

## 🤝 Contributing

Contributions are welcome! If you have suggestions for new features, encounter bugs, or want to improve the codebase, please feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.