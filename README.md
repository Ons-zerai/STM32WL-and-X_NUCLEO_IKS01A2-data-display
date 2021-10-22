# STM32WL-and-X_NUCLEO_IKS01A2-data-display


                                             /*****Display data from IKS01A2 and send it to a network server using LoRaWAN PROTOCOL *****/ 
                                                        ***********************************************************************
                                                         /// This project was built using STM32CubeIDE with HAL librairies ///


To use this driver, you must import the project named LoRaWAN_End_Node from STM32WL firmware then you ought to import the packages of X_NUCLEO_IKS01A2 then you activate
I2C2 ( PA11, PA12) ---

then go to sys_conf.h and enable the use of the sensor ( #define SENSOR_ENABLED   1   // 0->1 ),
then go to project properties and define  X_NUCLEO_IKS01A2  ( #define X_NUCLEO_IKS01A2 ) 
go to lora_app.c and copy the content given. 


/**** Don't forget to check the LoRa configuration such as the active region ******/ 
