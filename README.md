# [PSoC 6](https://www.cypress.com/products/psoc-6-microcontrollers-32-bit-arm-cortex-m4m0) MCU - Exploration
Exercises performed for the course **'IoT'** given at Hasselt University at the faculty of Engineering Technology.

## Prototyping Kit - [CY8CPROTO-062-4343W](https://www.cypress.com/documentation/development-kitsboards/psoc-6-wi-fi-bt-prototyping-kit-cy8cproto-062-4343w)
### Prototyping board
PSoC 6 family relies on the ultra-low-power architecture and uses dual-cores with a 150-MHz Arm® Cortex®-M4 as the primary application processor and a 100-MHz Arm® Cortex®-M0+ as the secondary processor for low-power operations. (Higher clock frequency = more power consumption)

### Supported Software
The [ModusToolbox](https://www.cypress.com/products/modustoolbox) is recommended to develop and program the PSoC 6 devkit. This software is also used in this course.

### [FreeRTOS](https://www.freertos.org/) Support
The board itself is FreeRTOS qualified. The FreeRTOS can be used by enabling it at 

```Tools >> Library Manager >> Libraries >> Check FreeRTOS >> 'Update'```

FreeRTOS is developed by 

## Excercise Hyperlinks
| Number | Excercise | Status |
| --- | --- | --- |
| 1. | Hello World | Completed |
| 2. | GPIO Interrupt | Completed |
| 3. | Button UART | **In Progress...** |
| 4. | FreeRTOS - Queues | **In Progress...** |

## License
[MIT](https://choosealicense.com/licenses/mit/)