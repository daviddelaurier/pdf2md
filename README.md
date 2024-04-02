# Technical Version:

## Marker is a powerful tool designed to convert PDF, EPUB, and MOBI files to markdown format. It outperforms the popular tool nougat in terms of speed (10x faster) and accuracy, particularly on non-arXiv documents. Marker minimizes the risk of hallucination by employing a pipeline of deep learning models that efficiently process the document.

### Key features for technical users:

-Versatile PDF support: Marker is optimized to handle a wide range of PDF documents, with a focus on books and scientific papers. It can extract text, detect page layout, and process complex elements such as equations, code blocks, and tables.
---
-Artifact removal: The tool automatically identifies and removes headers, footers, and other unwanted artifacts from the document, ensuring a clean and readable output.
---
-LaTeX equation conversion: Marker employs advanced techniques to detect and convert mathematical equations to LaTeX format, preserving their structure and readability in the final markdown output.
---
-Code block and table formatting: The tool intelligently recognizes and formats code blocks and tables, making the converted markdown document more organized and visually appealing.
---
-Multi-language support: Marker supports a variety of languages, with the ability to add new languages easily by modifying the settings.py file. This makes it adaptable to a wide range of use cases and user requirements.
---
-Hardware flexibility: The tool is designed to work seamlessly on GPU, CPU, or MPS (Apple's Metal Performance Shaders), allowing users to leverage their available hardware resources for optimal performance.
---
-Under the hood, Marker employs a sophisticated pipeline of deep learning models. These models work together to extract text from the input document, detect the page layout, clean and format individual blocks, and finally combine the processed blocks to generate the markdown output. By strategically limiting the use of autoregressive -- forward passes to equation blocks, Marker achieves a significant speed boost and reduces the risk of hallucination compared to nougat.
---


# Non-Technical Version:

## Marker is an easy-to-use tool that helps you convert PDF, EPUB, and MOBI files to a simpler format called markdown. It's much faster and more accurate than other popular tools like nougat, especially when working with non-academic documents. Marker is designed to give you clean, readable results without any confusion or errors.

### Key features for non-technical users:

-Works with many types of PDFs: Marker can handle a wide variety of PDF files, especially books and scientific papers. It can extract text, understand the layout of each page, and process complex parts like equations, code snippets, and tables.
---
-Removes unwanted elements: The tool automatically finds and removes headers, footers, and other unnecessary parts from the document, giving you a clean and easy-to-read output.
---
-Converts math equations: Marker uses advanced techniques to find mathematical equations in your document and convert them to a format called LaTeX, which helps maintain their structure and readability in the final markdown output.
---
-Organizes code and tables: The tool smartly recognizes and formats code snippets and tables, making the converted markdown document more organized and visually appealing.
---
-Supports multiple languages: Marker can work with various languages, and you can easily add new languages by making simple changes to a settings file. This makes it adaptable to your specific needs and requirements.
---
-Works on different devices: The tool is designed to work smoothly on different types of computers, including those with GPUs, CPUs, or Apple's Metal Performance Shaders (MPS). This means you can use Marker efficiently with the hardware you already have.
---
-Behind the scenes, Marker uses advanced AI models that work together to extract text from your input document, understand the layout of each page, clean and format individual parts, and finally combine the processed parts to create the markdown output. By intelligently focusing on specific elements like equations, Marker achieves a significant speed boost and reduces the risk of errors compared to other tools like nougat.
---

