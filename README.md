# Video RC Prototype
Drone video and RC control system with an Air Unit and a Ground Unit.

The system is built around the STM32H743RBT6 high-performance microcontroller and integrates an OV5640 camera with an RF communication module. The primary objective is to develop an indigenous and modular platform with control over the hardware, firmware, communication protocol, and overall system architecture.

The system consists of an Air Unit installed on the vehicle and a Ground/Remote Unit operated by the user. The Air Unit captures live video, handles vehicle-control interfaces, and communicates wirelessly with the Ground Unit through the RF subsystem.

# Major Components
Component                                                                                	Function
STM32H743RBT6	                                                                    Main processing and control MCU
OV5640                                                                            Camera	Real-time image/video capture
RF Module	                                                                        Wireless communication between Air Unit and Ground Unit
