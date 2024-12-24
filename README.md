Below is the English translation of the provided markdown content:

# ComfyUI PaintingCoderUtils Nodes

A collection of utility nodes designed for ComfyUI, offering a range of convenient image processing tools.
      
    
[中文说明](./README_CN.md)    
      
    

## 🌟 Features

- 💡 Simple and easy to use
- 🛠️ Practical functionality
- 🔌 Fully compatible with ComfyUI
- 🎨 Focused on image processing

## 📦 Installation Instructions

1. Navigate to ComfyUI's `custom_nodes` directory
2. Download the `ComfyUI_PaintingCoderUtils` folder
3. Restart ComfyUI

## 📚 Documentation

Please refer to the `README.md` file inside the `ComfyUI_PaintingCoderUtils` folder.

```bash
cd custom_nodes
git clone https://github.com/laofu-dev/ComfyUI_PaintingCoderUtils.git
```

3. Restart ComfyUI

## 🎯 Functional Nodes

### Dynamic Image Inputs
A tool node that combines multiple image inputs into a single list output.

Features:
- Supports dynamic addition and removal of image input ports
- Automatically ignores disconnected input ports
- Outputs a standardized image list format

Use Cases:
- Batch processing multiple images
- Merging multiple image sources
- Providing data for nodes that require image list input

### Remove Empty Lines
A text processing tool for cleaning up empty lines in text.

Features:
- Supports removing empty lines
- Supports trimming leading and trailing spaces
- Flexible output format options

### Image Resolution Adjuster
A utility node for adjusting image resolutions according to SDXL optimal aspect ratios.

Features:
- Supports all SDXL optimal resolutions (1:1, 9:7, 7:9, 3:2, 2:3, etc.)
- Adjustable scale factor for resolution scaling
- Configurable maximum and minimum resolution constraints
- Multiple extend modes (contain, cover, fill, etc.)
- Maintains aspect ratio while resizing

Use Cases:
- Preparing images for SDXL generation
- Batch resizing images to specific aspect ratios
- Standardizing image dimensions for consistent processing

## 🎨 Usage Examples

### Dynamic Image Inputs Node
1. Add the node to your workflow
2. Connect images to the input ports
3. The outputted image list can be used for further processing

### Remove Empty Lines Node
1. Input the text that needs processing
2. Choose processing options
3. Retrieve the processed text

## 🔧 Development Notes

### Project Structure

```
├── __init__.py
├── dynamic_image_input.py
├── remove_empty_lines.py
├── README.md
└── LICENSE
```

### Adding New Nodes
1. Create a new Python file in the project directory
2. Implement the node class
3. Register the node in `__init__.py`

## 📝 License

MIT License

## 🤝 Contributions

Issues and Pull Requests are welcome!

## 📞 Contact

- GitHub: [Your GitHub Homepage]
- Email: [Your Email]

## 🙏 Acknowledgements

- The ComfyUI Team
- The Impact-Pack Project

This README: 
