## EEG @ home
The COVID19 quarantine led to the documentation of the installation details for a single-user/experimenter EEG setup to encourage and help those that have to work remotely and isolated.


### User: 
- 1 male (causacian)
- Hair size: average (5cm +-1)
- Hair type: 2a (source: https://www.headcurve.com/wp-content/uploads/2018/09/Types-of-Hair-Chart-Headcurve.com_.webp)
- Hair density: Medium density (source: https://www.wikihow.com/Determine-Hair-Type#Determining-Hair-Density)

### Equipment:
 - **Amplifier**: Brain Products LiveAmp 32 ([technical specifications](https://www.brainproducts.com/productdetails.php?id=63&tab=2))
 -    **EEG-cap & Electrodes**: 32  [actiCAP](https://www.brainproducts.com/productdetails.php?id=4)  active electrodes in a 56cm EEG-cap.
 - **Acquisition software**: [BrainVision Recorder](https://www.brainproducts.com/productdetails.php?id=21) v1.22.0001

### Steps:

#### 1. insert all electrodes in the EEG-cap slots (*time: 20min*) ![step1](https://raw.githubusercontent.com/athanoid/eeg-at-home/master/images/step1.jpg)

#### 3. flip the cap & apply gel inside the cavities (time: 5-8min) 
 
 ![enter image description here](https://raw.githubusercontent.com/athanoid/eeg-at-home/master/images/step2.jpg)
##### ![gel in cap](https://raw.githubusercontent.com/athanoid/eeg-at-home/master/images/put_gel.gif)
#### 4. [a] place your head inside the cable opening, [b] wear the cap carefully and clip the box in your shirt, [c] plug and switch the amp ON (*time: 2-3 min*). ![enter image description here](https://raw.githubusercontent.com/athanoid/eeg-at-home/master/images/step3.png)

> Note: I chose to hold the amp in order to control it but if you want
> you can place it inside the cap pocket before wearing it.

#### 5. massage softly each electrode (time: 3min)

#### 6. first impedance check: Gnd was at 10 kOhm (time: 2min)![enter image description here](https://raw.githubusercontent.com/athanoid/eeg-at-home/master/figures/impedance_before.png)
#### 7. use the syringe and insert additional gel on each electrode with the help of a mirror (*time: 30mim*) 
 ![enter image description here](https://raw.githubusercontent.com/athanoid/eeg-at-home/master/images/step4.jpg)
 
#### 8. second impedance check:
 
  ![enter image description here](https://raw.githubusercontent.com/athanoid/eeg-at-home/master/figures/impedance_after.png)
  
##### A more detailed impedance distribution: 
![enter image description here](https://raw.githubusercontent.com/athanoid/eeg-at-home/master/figures/impedance_topoplot.png)


### Detailed Impedance table:
| Electrode| kOhm| 
|--|--|
|Fp1: |         4|
|Fz:   |       15|
|F3:     |      8|
|F7:    |     11|
|FT9:   |       1|
|FC5:   |      12|
|FC1:    |      8|
|C3:   |       9|
|T7:      |    19|
|TP9:      |   17|
|CP5:    |      3|
|CP1:     |    10|
|Pz:    |       7|
|P3:    |      11|
|P7:      |    17|
|O1:  |        0|
|Oz:   |        5|
|O2:    |      17|
|P4:        |   2|
|P8:    |      10|
|TP10:    |     8|
|CP6:   |      16|
|CP2:  |       21|
|Cz:    |       8|
|C4:      |    17|
|T8:     |      9|
|FT10:      |   8|
|FC6:    |     14|
|FC2:    |      6|
|F4:    |      11|
|F8:     |     16|
|Fp2:    |      4|
|Gnd:     |     4|
|Ref:    |      9|


---
 **TOTAL TIME**: 43min (+20 if the electrodes are not clipped in the cap) 
--
-- Total gel consumption: 1,1/2 syringes 
![enter image description here](https://raw.githubusercontent.com/athanoid/eeg-at-home/master/images/syr.jpg)


### Data:
[Acquired test data](https://github.com/athanoid/eeg-at-home/tree/master/data): 5 min eyes open [EO] and 5 min eyes-closed [EC] 



![EC spectopo](https://raw.githubusercontent.com/athanoid/eeg-at-home/master/figures/spectopo_EC.png)Figure: Sample PSD of eyes closed after 1hz high-pass filtering and re-referencing to average. Alpha at 10Hz can be observed from the occipital electrodes.

### Conclusions and final remarks
This notes showcase the feasibility of a single-user/experimenter EEG setup for acquiring data when additional help is not available (e.g. due to quarantine).
Current data show that we are able to install  the complete EEG equipment in approximately 60 minutes and keep the impedance under 20 kOhms. Finally, a test dataset during resting state (eyes-open/closed) was generated for test and validation. Preliminary results show Alpha activity at 10Hz measured from the occipital electrode locations as anticipated.
