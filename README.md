# ECE425-Arithmetic-Calculator-Final-Project

# Introduction
This project consisted of implementing an arithmetic calculator using EduBase Keypad buttons as inputs. The user interacts with the keypad buttons and visualization of the input and output is provided through the teraterm pro terminal which was used in previous UART experiment in the lab. The calculator functions by printing a layout of the keypad buttons, prompting the user for input (values and operation) and lastly prints out the result of the calculation.  This report covers the components used, microcontroller peripherals involved, detailed functionality, challenges encountered and solutions implemented. 
# Results 

# Background and Methodology
In this project, we used the following embedded systems applications: GPIO, SysTick, and UART.
  - GPIO: used for the keypad (which in turn was used as the input for numbers and operations) and the EduBase board LEDs, which lit up depending on which keypad button was pressed
  - SysTick Timer: used for debouncing, since the keypad does not have any debouncing hardware. This allowed for the desired inputs to be made (one input for each button press)
  - UART: used to display the calculator layout, the user’s inputs, and the result

# Functional Block Diagram

# List of Components

# Pinout Table

