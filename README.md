<h1>STM32_FreeRTOS : Counting Semaphores</h1>

<li>STM32_FreeRTOS Example with STM32F3Discovery Kit in STM32CUBEIDE</li>

<li><i><b>FreeRTOS</b></i> is used in this project as RTOS Library.</li>

<li>If it's not necessary don't regenerate the code from CUBE! If you need to regenerate then you should remove default generated parts of code (handles, functions and etc.) for CMSIS OS!</li>

<h3>Important points</h3>

<ol>
  <li>xSemaphoreGive(semaphore) => This function releases the semaphore</li>
  <li>xSemaphoreTake(semaphore, delay) => This function acquires the semaphore</li>
  <li>In <b>Binray Semaphores</b> you can just <i>release</i> semaphore in the task which have <i>acquired</i> it!</li>
  <li>In <b>Counting Semaphores</b> you can <i>release</i> semaphore at <i>any point of code</i>!</li>
</ol> 

![image](https://github.com/MuhammadRezaHeidary/STM32_FreeRTOS/assets/50994989/a357ad40-bffa-4a89-9200-ced01092da1a)
