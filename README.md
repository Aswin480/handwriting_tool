# Text to Handwriting 📝

A fast, fully customizable, modern web application that converts typed text into an image that looks perfectly handwritten. Whether you need to generate "handwritten" assignments, notes, or personalized letters, this tool seamlessly matches text onto physical paper backgrounds.

## Features ✨

* **Auto-Save**: Everything you type is automatically saved using local browser storage. You will never lose your work if the page refreshes.
* **Premium User Interface**: Features a sleek, distraction-free "Glassmorphism" interface with smooth animations and dynamic layouts.
* **Complete Position Control**: Need room for a logo or a header? Adjust the exact **Left Margin** and **Top Margin** in pixels.
* **Custom Paper Sizes**: Upload any image of a piece of paper (or notebook) to use as your background, and adapt the overall **Paper Height** dynamically to fit it.
* **Bring Your Own Handwriting**: Upload your own custom `.ttf` or `.otf` generated handwriting font file to make the handwriting indistinguishable from your own.
* **PDF Export**: Automatically compile all generated pages into a single beautiful PDF.

## How to use 🚀

1. Clone or download this repository to your local machine.
2. Ensure you have Node.js installed.
3. Open your terminal in the directory and run `npm install`.
4. Run `npm run dev` to serve the application locally.
5. Open your browser to the provided local URL (e.g., `http://localhost:5000`).

## How to Add Your Own Handwriting ✍️

Since interpreting an image of your handwriting directly into a font is a tough AI problem, you can use a font generator service to help!

1. Head over to [Calligraphr.com](https://www.calligraphr.com/en/).
2. Print out their template grid, write your letters in the boxes, and snap a picture of it.
3. Upload it to their website to generate your custom `.ttf` font file.
4. Come back to this **Text to Handwriting** app.
5. In the **Handwriting Options** panel, upload your `.ttf` file. Your text will instantly update to perfectly replicate your actual handwriting!

## License 📄
Available freely under the MIT License.
