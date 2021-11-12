# rotosecure basics

##### Team 
Chase Westlake, Kaden Taylor, Ethan Pyle, Ben Kennedy

##### Context
Capstone project for 2021 Fall Electronics and Computer Engineering Technology (ECET) at Camosun College

##### Purpose
Drone designed using skills developed in ECET to showcase competencies learned and ability to accomplish technical tasks in a team

##### Intent
Surveilia is an autonomous drone that patrols areas on designated flight paths. It can detect and report humans to ground-station software; as well, it can acquire flight data for records and graphical display. Surveilia uses OpenCV for computer vision and ArduPilot flight automation. Onboard the drone is a Raspberry Pi Compute Module 4 (CM4) and a Kakute F7 V1.5 Flight Controller. The CM4 relays data back to the ground station, while the F7 allows autonomous flight and control.  




## Bill of Materials & Accounting

### Motors and components 

purchased from: https://www.getfpv.com/ 

##### In American dollars 
    - shipping: $18.00 
    - insurance: $3.06 (6% of order).
    
** Conversion rate changes as the USD has shifted a lot over the course of the last few months. The proper conversions were used directly from Chase Westlake's VISA statement to be as accurate in CAD as possible.

    Cost (USD): $292.56
    Cost (CAD): $367.17
    
    *These values are potentially misleading. Prices are in USD. 
    Acquired: 
    ~ 4x T-Motor VELOX VELOCE V2207.5 V2 Motor - 1750 kv (Royal Blue)                       $70.00
    ~ HQPROP DP 5X4.3X3V25 Propeller (Set of 4 - blue)                                      $2.99
    ~ XILO 1250 mAh 6s 75c Lipo Battery                                                     $29.99
    ~ ToolkitRC M7 200W 10A 2-6s DC Multifunctional Balance Charger                         $39.99
    ~ SKYSTARS KO BLHELI_32 4-IN-1 3-6S 30X30 ESC - 45A                                     $35.99
    ~ RUNCAM LIPO GUARD BAG                                                                 $14.99
                                                                                            + 2 x (taxes, shipping, and insurance)
                                                                                            
### Inertial Measurement Unit (IMU)

    Acquired:
    ~ Gikfun GY-521 MPU-6050 3 Axis Accelerometer Gyroscope Module 6 DOF 6-axis            $12.98
      accelerometer Gyroscope Sensor Module for Arduino DIY (Pack of 3) EK1091x3C             


### Computers and accessories 
purchased from - https://www.canakit.com

    Cost (CAD): $223.27 CAD
    Acquired 
     ~ Raspberry Pi - 32 GB Memory Card w/NOOBS                                           $12.95
     ~ Raspberry Pi NoIR Camera - 8 Megapixel (V2)                                        $39.95
     ~ Kakute F7 Flight Controller/H7 V2 VTx                                              $140.37 w/shipping/handling + $30.00 duty  
     ~ CM4 - Lite, CM4002000 Pishop.ca                                                    $62.21 ($12.00 shipping, $2.96 tax)


### Kaden's Orders
    ~Black Series 1100mAh 22.2V 6s 100c Lipo                                              $62.99
    ~BN-220 GPS                                                                           $24.99
    ~XT60H battery plugs 10 pairs                                                         $16.46
    ~M3 bolts and nuts                                                                    $15.00
    ~Registration & License                                                               $15.00
    
#### Total Cost - Kaden
    
    Current Total Cost:             $134.44
    Camosun Offset:                 $40.19
    4-way Total (each person:       $23.56

#### Total Cost - Chase

    Current Total Cost:     $701.78
    Camosun Offset:         $209.81
    4-way Total:            $122.99
    
    
### Total Cost:
    
    Current Total: $836.22
    Chase & Kaden differential: Kaden 16.08% ---- $250 (From Camosun) * 16.08% = $40.19 from Camosun to Kaden
    
    Total 4-way Cost:       $146.55


* Look to  double asterisk at top of README if there are any questions about the cost. 

         
         
         
## References

### GUI
Page creation in XAML and C# 

    - https://www.youtube.com/watch?v=aBh0weP1bmo
                               
    Most recent reference: https://www.youtube.com/watch?v=OJygSefHVr0&t=87s

### PID
PID Tuning

    - Betaflight tuning: https://github-wiki-see.page/m/betaflight/betaflight/wiki/PID-Tuning-Guide
    
    - GETFPV tuning: https://www.getfpv.com/learn/fpv-essentials/fpv-drone-basic-pid-tuning-rates/
    
    - Beyond Earth Betaflgiht 4.2 PID rapid tuning: https://fpvbeyond.earth/betaflight-4-2-pid-tuning-quick-and-dirty/?lang=en
    

#### November 12, 2021: The PID was orignally planned to be developed by Surveilia. However, we quickly came to the conclusion that any flight controller design was well 
#### outside of bounds of our scope. Instead, we used BetaFlight and ArduPilot for our PID. It is important to note that much of PID tuning relies on evaluating 
#### black box data. At this point, a mild hand tune is all we will be doing. A comprehensive black box tune probably will not be done within the scope of the project. 




 PID design links

    - All about Circuits https://www.allaboutcircuits.com/technical-articles/an-introduction-to-control-systems-designing-a-pid-controller-using-matlabs/
    
    - PID for Dummies https://www.csimn.com/CSI_pages/PIDforDummies.html

    - Control Tutorials for MATLAB https://ctms.engin.umich.edu/CTMS/index.php?example=Introduction&section=ControlPID
    
    - Control Tutorials for MATLAB 2 https://ctms.engin.umich.edu/CTMS/index.php?example=MotorSpeed&section=ControlPID


Accelerometer Tutorial 

    - https://mschoeffler.com/2017/10/05/tutorial-how-to-use-the-gy-521-module-mpu-6050-breakout-board-with-the-arduino-uno/
                       
    - Pi setup guide: https://www.raspberrypistarterkits.com/guide/raspberry-pi-accelerometer-gyroscope/
    
    - MPU6050 package installation https://pypi.org/project/mpu6050-raspberrypi
    
    - MPU6050 Guide: https://electrorules.com/complete-guide-on-mpu6050-gyroscope-accelerometer-sensor-module/
    
    - MPU6050 Guide #2: https://www.electronicwings.com/sensors-modules/mpu6050-gyroscope-accelerometer-temperature-sensor-module


I2C Communication Tutorial 
                                    
    - https://www.electronicshub.org/basics-i2c-communication/


### Pi Zero W

Shell Scripting Tutorials

    - https://www.educba.com/software-development/software-development-tutorials/shell-scripting-tutorial/

### Drawings
Drone CAD drawings built in: Fusion 360

### ArduPilot

    - Mission planner: https://ardupilot.org/planner/index.html#home
    - Github Repo: https://github.com/ArduPilot/ardupilot

