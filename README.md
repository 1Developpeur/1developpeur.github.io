# 🌑 Onyx Toolbar Customization Script

This document provides an in-depth look at how the customization script operates, allowing you to understand the logic and functionality.

## ✨ How It Works

The Onyx Toolbar Customization Script is designed to provide a seamless and intuitive way to customize the appearance of the Onyx Toolbar for SeelenUI. Here’s a breakdown of its core components and how they interact:

### - **Loading Configuration Files**

The script begins by loading two essential files:
- **`onyx_variables.json`**: This file contains a list of customizable variables, including colors, sizes, and other properties that define the toolbar's appearance.
- **`onyx_toolbar_default.yaml`**: This YAML file serves as the template for the toolbar's configuration. It includes placeholders for the variables defined in the JSON file.

### - **Dynamic Control Generation**

Once the configuration files are loaded, the script dynamically generates user interface controls based on the variables defined in the JSON file. This includes:
- **Sliders** for numerical values (e.g., border width, opacity).
- **Color pickers** for selecting colors, which allow users to visually choose their desired shades.
- **Dropdowns** for selecting styles (e.g., border styles).

Each control is linked to a specific variable, and as users interact with these controls, the script updates the corresponding values in real-time.

## 🎥 Preview

[Preview Video](https://github.com/user-attachments/assets/2f9c393b-0a06-4820-aa66-e5fe070c6f9b)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [1Developpeur](https://github.com/1Developpeur)
