<div align="center">
<img src="assets/img/SlideWrangler_logo.webp" alt="An Aweosme Slide Wrangler logo here" width="150">

### SlideWrangler: Automated PowerPoint Slideshow Generator
</div>

**SlideWrangler** is a Python automation tool that instantly converts a folder of images into a polished, widescreen PowerPoint presentation.

Featured in the blog post: [From Flash Drive Frenzy to Slideshow Serenity](https://blog.beaubremer.com/posts/slideshow_serenity/)

-----

## 🚀 The Solution

If you've ever been handed a flash drive full of unorganized photos minutes before an event with the request to "put these on the big screen," you know the struggle. Manually inserting, resizing, and centering hundreds of images is tedious and prone to error.

SlideWrangler handles the heavy lifting for you. It processes raw image files—correcting orientation and resizing them for HD screens—and generates a clean, ready-to-present `.pptx` file in seconds.

## ✨ Key Features

  * **Smart Validation**: Automatically detects and processes valid image files (`.jpg`, `.png`, `.bmp`, `.gif`), skipping corrupt files or non-image documents.
  * **EXIF Auto-Rotation**: Reads camera metadata to ensure portrait and landscape photos are oriented correctly.
  * **Screen Optimization**: Resizes all images to fit within a 1920x1080 (Full HD) container, significantly reducing file size without sacrificing projection quality.
  * **Uniform Formatting**: Standardizes all inputs (including PNGs with transparency) into compatible JPEGs to ensure smooth playback.
  * **Presentation Ready**: Outputs a standard 16:9 widescreen presentation with every image perfectly centered and scaled to fit.
  * **Zero Clutter**: Operations are handled in a temporary directory that is automatically deleted upon completion, leaving your source folder untouched.

## 🛠️ Requirements

  * **Python 3.x** installed on your system.
  * The following Python libraries (handled via `requirements.txt`):
      * `Pillow` (for image processing)
      * `python-pptx` (for PowerPoint generation)

## 📦 Installation

1.  **Clone or Download** this repository.
2.  **Install Dependencies** via your terminal:

```bash
pip install -r requirements.txt
````

## 💻 How to Use

1.  **Run the Script**:
    Navigate to the directory where you saved the script and run:
    ```bash
    python create_slideshow.py
    ```
2.  **Provide Source Path**:
    When prompted, paste the full path to the folder containing your images.
      * *Example:* `C:\Users\YourName\Desktop\EventPhotos`
3.  **Retrieve Slideshow**:
    Once processing is complete, your new presentation (`Generated_Slideshow.pptx`) will appear on your Desktop.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

-----

\<div align="center"\>
\<sub\>Created by Beau Bremer (KnowOneActual)\</sub\>
\</div\>