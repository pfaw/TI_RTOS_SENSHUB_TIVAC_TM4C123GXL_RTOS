# TI_RTOS_SENSHUB_TIVAC_TM4C123GXL_RTOS

- This project makes the TIVA C or TM4C123GXL interface and communicate the the Texas Instrument BOOSTXL-SENSHUB Sensor Hub  (or senshub)
- The final result is that of the example that is offered by TI in code composer studio for the TIVA C. However this project does so using TI-RTOS
- The project started from a code composer studio example. It had senshub working with the TM4C129g, uisng TI-RTOS.
  - I changed the pins used and changed the written API to what is used when using the TM4C123GXL MCU when using TI libraries as opposed      to when using the TM4C129g

- You can use this project as a jump off point if you're using the TIVA C, senshub, and are aiming to use TI-RTOS as middleware in your project. If you have the hardware and connections made, the project does the initalizations necesary and the data should be read and printed to your console in Code Composer Studio.

Instructions:
  1) Open Code Composer Studio after downloading the zip
  2) You click on: projects -> Import CCS Projects
  3) Click on the extracted project
  4) Tick the box that says "Copy projects into workplace"
  5) Clean and build
  6) Have fun
