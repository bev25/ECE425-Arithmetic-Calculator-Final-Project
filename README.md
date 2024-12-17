# ECE425-Arithmetic-Calculator-Final-Project

# Introduction
This project consisted of implementing an arithmetic calculator using EduBase Keypad buttons as inputs. The user interacts with the keypad buttons and visualization of the input and output is provided through the teraterm pro terminal which was used in previous UART experiment in the lab. The calculator functions by printing a layout of the keypad buttons, prompting the user for input (values and operation) and lastly prints out the result of the calculation.  This report covers the components used, microcontroller peripherals involved, detailed functionality, challenges encountered and solutions implemented. 
# Results 

![Division by Zero Case](https://github.com/user-attachments/assets/85562763-6484-4079-ba99-7cb8dfee074b)

![Negative Numbers Case](https://github.com/user-attachments/assets/3b47c7e1-eb30-41aa-871e-ced4b3749226)

![Reset Button Case](https://github.com/user-attachments/assets/c93fd9a2-2870-4dde-b22c-97e092dbebda)

![Regular Operation Case](https://github.com/user-attachments/assets/4092ba08-c5ad-4565-aa48-d553a3884c09)


# Background and Methodology
In this project, we used the following embedded systems applications: GPIO, SysTick, and UART.
  - GPIO: used for the keypad (which in turn was used as the input for numbers and operations) and the EduBase board LEDs, which lit up depending on which keypad button was pressed
  - SysTick Timer: used for debouncing, since the keypad does not have any debouncing hardware. This allowed for the desired inputs to be made (one input for each button press)
  - UART: used to display the calculator layout, the user’s inputs, and the result

# Functional Block Diagram
<img width="461" alt="Block Diagram" src="https://github.com/user-attachments/assets/cb4e4c46-11f5-4e7e-a596-2fafd9a38043" />



# List of Components
<img width="532" alt="Component List" src="https://github.com/user-attachments/assets/d3eb1940-ccae-4243-a8b8-08ffe63221ae" />


# Pinout Table
<img width="397" alt="Pint Out Table" src="https://github.com/user-attachments/assets/519de9f2-24c1-49d9-8c42-c54c56e97a12" />

