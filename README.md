
# STM32 FreeRTOS Multitask Lab

## Overview
This project demonstrates multitasking on the STM32F446RE Nucleo board using FreeRTOS. Multiple tasks run concurrently, showcasing task scheduling, synchronization, and basic RTOS concepts for embedded systems.

## Hardware
- **Board:** STM32F446RE Nucleo
- **Debugger:** ST-Link V2
- **Peripherals:** User LED, push button (optional)

## Approach
This implementation uses STM32 HAL drivers and FreeRTOS middleware:
- High-level abstraction for hardware access
- FreeRTOS kernel for task management
- Example tasks: LED blink, message print, etc.

### Key FreeRTOS Concepts Used
- `xTaskCreate()` — Task creation
- `vTaskDelay()` — Task timing
- `vTaskStartScheduler()` — Scheduler start
- Task priorities and stack sizes

## Project Structure
```
├── Core/
│   ├── Inc/           # Header files
│   ├── Src/           # Source files
│   └── Startup/       # Startup files
├── Drivers/           # STM32 HAL and CMSIS drivers
├── Middlewares/       # FreeRTOS source
├── Debug/             # Build output
├── *.ioc              # STM32CubeMX configuration
```

## Learning Objectives
- Understand FreeRTOS task creation and scheduling
- Use STM32 HAL with FreeRTOS
- Structure STM32CubeIDE projects for RTOS
- Compare multitasking with bare-metal approaches

## Getting Started
1. **Clone this repository:**
   ```sh
   git clone https://github.com/Ama-Andam/stm32-freertos-basics.git
   ```
2. **Open in STM32CubeIDE** (or compatible IDE)
3. **Build and flash** to your STM32F446RE board

## Demo
*Add screenshots, diagrams, or video links here*

## References
- [FreeRTOS.org](https://www.freertos.org/)
- [STM32 HAL Documentation](https://www.st.com/en/embedded-software/stm32cube-mcu-package.html)
- [STM32CubeIDE](https://www.st.com/en/development-tools/stm32cubeide.html)

---
