# Figma Unity Importer

> A convenient Figma plugin that helps you quickly import Figma designs into Unity projects.

---

## 🚀 Quick Start

1. **Set Global Configuration**
   - Set the global configuration `FigmaGlobalConfig` in the plugin

2. **Create Import Task**
   - Right-click in the Project window
   - Select `Create/Figma/Import Task`

3. **Get Figma Link**
   - Right-click on a node in Figma
   - Select `Copy/Paste as` / `Copy link to selection`
   - Paste the link into the task panel

4. **Import**
   - Click the Import button to complete

---

## ✨ Features

### Global Asset Management

Unified management of import settings through global configuration assets.

![Global Configuration](./images/global.png)

### Task Asset Management

Each import task has independent configuration options.

![Task Configuration](./images/task.png)

### 🎨 Custom Font Export Range

Allows you to customize the font export range, giving you flexible control over which fonts need to be exported.

![Font Configuration](./images/font.png)

### 🔧 Custom Script Processing

Supports custom post-processing scripts to handle imported assets according to your specific needs.

**Example Script:** `FigmaImportPostprocessorDemo.cs`

### 🏷️ Prefix Logic Support

Automatically identify and process different component types through node naming prefixes:

- **`img-`** - Merge and export as Image component
- **`btn-`** - Merge and export as Button component
- **`ign-`** - Ignore export

![Prefix Example 1](./images/pre.png)
![Prefix Example 2](./images/pre2.png)

---

## 📝 Developer

**StarAnise Studio**
