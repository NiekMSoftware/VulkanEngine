# Personal Vulkan Project
Welcome to my personal Vulkan project! This repository contains a custom-built game engine with the use of the VulkanAPI
for high-performance rendering. The engine in this case is purely designed for my personal learning and experiments
with Vulkan's powerful graphics capabilities.

---

## Structure
- `includes` - External includes (e.g., Vulkan, GLFW)
- `lib` - External libraries (e.g., Vulkan, GLFW)
- `shaders/` - Vulkan shader files
- `src/` - Engine Source Code
  - `core/` - Core engine systems

---

## Setup
### 1. Install Vulkan SDK
Before compiling this project, you must install the Vulkan SDK on your system.

#### **Windows**
1. Download the Vulkan SDK installer from the [Vulkan SDK homepage](https://vulkan.lunarg.com/sdk/home).
2. Install the SDK and set the `VULKAN_SDK` environment variable: `C:\VulkanSDK<version>\Setup-Env.bat`

#### **Linux**
Make sure to follow [this guide](https://linuxconfig.org/install-and-test-vulkan-on-linux), if you'd like to install for Linux.

### 2. Clone this repository
Clone this repository to your local machine:
```bash
git clone git@github.com:NiekMSoftware/VulkanEngine.git
cd VulkanEngine
```

> This will get updated further down the line.