# 📦 工程模板仓库 (Template Hub)

> 这里存放着我常用的项目工程骨架，新项目开发时直接从这里复制，拒绝重复造轮子。

## 📂 模板清单

### 1. 嵌入式开发 (Embedded)
- **`stm32-hal-template/`**: 
    - 基于 STM32CubeMX 生成的 HAL 库纯净工程。
    - **已配置**: 72MHz 时钟, SysTick, 基础 GPIO。
    - **适用**: 所有 STM32F1 系列的新项目。
- **`esp32-idf-template/`**: 
    - ESP-IDF 框架的基础结构。
    - **已配置**: WiFi 连接组件, 日志系统。

### 2. 机器视觉 (Vision)
- **`opencv-cpp-base/`**: 
    - C++ 调用 OpenCV 的 CMake 工程结构。
    - **包含**: `CMakeLists.txt` 配置, 基础图像读取显示代码。
- **`python-vision-env/`**: 
    - Python 视觉项目的基础目录。
    - **包含**: `requirements.txt`, 虚拟环境配置说明。

### 3. 软件与工具 (Software)
- **`qt-widget-app/`**: 
    - Qt Widgets 应用程序的基础框架。
- **`cpp-cli-tool/`**: 
    - 纯 C++ 命令行工具的标准结构。

## 🚀 如何使用

1. **选择模板**: 根据新项目的需求，在上述列表中找到对应的文件夹。
2. **复制**: 将整个文件夹复制到你的工作区（如 `D:/Projects/`）。
3. **重命名**: 将文件夹重命名为你的新项目名称（如 `prj-new-car`）。
4. **清理**: 删除旧的 `.git` 文件夹（如果有），重新初始化 Git 仓库。

## 📝 维护记录
- **2026-05**: 初始化仓库，添加 STM32 和 OpenCV 基础模板。