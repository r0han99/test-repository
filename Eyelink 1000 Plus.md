## **Eyelink 1000 Plus**

[TOC]

---

### **Details and Specifications** 

* Eyelink 1000 Plus can be used in a Behavioural, MRI, EEG and MEG labs

* It can be used for people of all ages from infants to elderly, also in special studies for non-human primates. 
* System can be configured in two modes
  * Head-Stablized and Head-Free Remote Mode 
* Sampling Rate - 2000hz
* Real-Time Access to Gaze data and Binocular Tracking is possible in all modes 

### **Camera**

* Modular with Multiple mounting options 
  * Arm Mount ( Best option for Infants )
  * Tower ( Largest Range of Tracking )
  * Desktop Mount 
  * Primate Mount 

### **Computer**

* There are two computers which has the feedback from the camera
  * Host PC - Dedicated to eye tracking 
    * Uncompromised  data quality without affecting stimulus presentation.
  * Display PC used for Stimulus Presentation 

* Host and Display connected via ethernet 

### **Software**

#### **Experiment Builder**

Graphical programming inferface for experiment building representing a trial.

#### **Data Viewer**

* Viewing 

* Processing 

* Analysing 

  Gaze Data

---

## Desktop Mount Configuration

**Connection Steps**

* Desktop mount uses 16 or 25mm Lens

Steps to connect Host and Display PC 

1. For the desktop mount it doest matter whether which illuminator plug goes into which port. 
   * Connect both illuminator plus ( AUX like plugs ) into the connectors on the Eyelin

2. Next power cable to eye tracker to Outlet
3. **Black Eithernet** cable to the eye tracker to the HostPC
4. **Blue Eithernet** to the HostPC to the DisplayPC 
5. In MACOS
   1. System Preferrences → IP Address: 100.1.1.2 → Subnet Mask: 255.255.255.0



**Specifications - Desktop Mount**

* Trackable Range is 32 Degrees Horizontally and 25 Degress Vertically
* Distance from the participants eye to the Monitor should be atleast 1.75 times the width of the Monitor. 
* Eyes should be aligned to the Top Level of the Monitor 
* Position the eyetracker in a way where the distance between the camera and the eye-tracker is about 55cm 
* Eye tracker should be high as possible on the mount.

**Booting** 

* Startup the Host PC → This will automatically start the Eyelink software.
* Click Offline → Exit Eyelink → From the File Manger → Click Configuration Button → Screen Settings 
  * Enter the accurate Screen Dimensions 
    * Measure Width and Height in Millimeters. ( Dont Include the Side Bezels )
  * The Resolution setting is not mandatory.
* In a Head-free setting we can leave the Remote Mode settings to default.
* Camera to Screen Distance
  * Measure the Distance between the Lens and the Screen.
  * Enter the Distance in Millimeters.
* We can either use 16mm ( Accounts for Wider perspective ) or the 25mm ( for closest Precision )

---

## Desktop Mount Remote Participant Setup

* Place a target sticker on the forehead 
* In binocular mode, sticker should be centered between the two eyes.
* It is recommended to the check the camera image in the display PC which can be done by following.
  * Click → Image to Display PC or Click "Enter".
* We can check the Global view, and Eye views using the Left and Right keys.
* The Participant's Seating Height should be aligned with the top of the display monitor.
  * Adjust the Distance of the participant and stabilize it when the Target Sticker shows a distance of between **550 to 600mm**
  * The System will track, 
    * 500-700mm for 16mm lens,
    * 530-670mm for 25mm lens
* Point the Camera so that the eye is roughly centered in the Camera Image.
  * Click the participant's eye to center the observation circle ( red circle )
  * Binocular mode requires each eye to be clicked seperatelely
* In the cases where we are tracking only one eye, it should be verified in the software page whether the right eye is selected. 
* Cross-Hairs will be displayed on the select eyes.
* Switch to Eye Camera using Arrow keys → Focus to Minimize Size of Corneal reflection → CR is small as possible.
  * Threshold values of CR and Pupil
    * Dark Blue and Cyan Should be only inside the pupils, Appearance of blue outside of Pupils will disrupt the data
    * Manual Adjustment is required if this case is encountered.



## Caliberation 

* During Caliberation the participant will fixate a Series of Targets on the Display PC Monitor 

* Caliberation maps position of the eye on the camera to the Gaze Position on Screen.
* In order to begin caliberating 
  * In the HostPC →  Set Options → (Under Caliberation and Validation ) Select Point Caliberation
    * Back at the Main Screen → Click Caliberate ( on the right ) or press "C"
* Instruct the participant to fixate the target and to follow that target as it moves.
  * Instruct them to keep looking at the target until it moves 
* The Black area on the Host PC Represents the display PC monitor. And the D cursor represents the current position of the Eye in Camera Image.
* When the participant is fixating the first target and the gaze cursor ( D ) is steady
  * → Press the Spacebar or Click Accept Fixation to Start Caliberation.
  * The Caliberation will Automatically Proceed after this point.
* In the Host PC the the caliberation will draw cross hairs to ensure the pattern of the crosshairs matches the pattern of the targets.
  * ![image-20230127141529081](/Users/rohan/Library/Application Support/typora-user-images/image-20230127141529081.png)

* If a Cross Hair looks out of place click "Back Space" to rollback to the previous caliberation point 

### Validation 

* After Caliberation is done press "V" on the Keyboard to Validate. 
  * The Validation procedure allows us to validate the accuracy of the caliberation. 
* When the participant is fixating the first target and gaze cursor (D) is ready, press "spacebar" or Click Accept Fixation to Start Validation
*  To participant Validation is similar to caliberation
  * But on the Host PC will reflect the measured position of the eye on the Display PC

* Validation will report the accuracy for each point, in degrees of visual angle
  * For healthy adult participants with normal vision, we recommend using criteria of 0.5 degrees or less average error and 1.0 degree or less maximum error.

Once Validation is done Click → Accept to Go Back to the Main Screen. 

Then Click Output Record or "O" to Proceed with the Experiment. 

---

### 

