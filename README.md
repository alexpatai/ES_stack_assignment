# ES_stack_assignment

Code can be found on the master branch.

Write a FreeRTOS application for your Nucleo Development Board which fulfills the following requirements:

Create three tasks that allocate memory on the stack, e.g. using memory allocation, recursion, etc.
A fourth task shall periodically output the stack size and the remaining stack size of these tasks using the corresponding global structs of the tasks (osThreadAttr_t) and the function osThreadGetStackSpace()
The output of the stack size and remaining stack size should be done by using a UART interface of the Nucleo board.
Hint: The transmit via UART can be done by retargeting the "printf" function. You will need to write your own "_write" function to be able to use "printf" accordingly.

In order to submit your assignment please upload a ZIP file by using the Assignment Activity within this self study session.
The ZIP file has to contain the following files:

The main.c and additional source/header files you created to solve this assignment
A screenshot which shows that you have tested your application - you should prove that the above mentioned requirements are fulfilled and tested
