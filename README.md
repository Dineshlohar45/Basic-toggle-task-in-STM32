# Basic-toggle-task-in-STM32
Basic toggle task in STM32 for the practical
Explanation
Initialization
System Clock Configuration: Configures the system clock using HSI (High-Speed Internal) oscillator.
GPIO Initialization: Sets up GPIO pin PB1 as an output pin for the LED.
TIM2 Initialization: Initializes TIM2 for timestamping and other timing-related purposes.
Task Creation
vTask_LED: A FreeRTOS task that toggles the LED connected to GPIO pin PB1 every second. It uses the vTaskDelayUntil function to ensure it runs periodically.
