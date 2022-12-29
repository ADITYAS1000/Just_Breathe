# Embedded Challenge : Just Breathe
NYU RTES Fall 2022 project : Just Breathe

In the case of Sudden Infant Death Syndrome (SIDS), a baby less than 1 year old experiences a sudden and unexpected death during sleep. There are no indications of illness, no prior symptoms, and occurs in otherwise healthy infants. Unfortunately, the direct cause of SIDS is unknown.

The objective of this semester’s embedded challenge is to build an embedded system that can determine if a person has stopped breathing for more than 10 seconds, after which, a trigger is activated as a notification or an “alert” that something is wrong.

### Approach Used: 
A flex(pressure sensor) attached to a strap wrapped along the the baby's belly will be able to measure the movement of breathing and hence would be able to detect absence of breathing thereby triggering a timer for 10 seconds and causing an alert after 10 seconds on inactivity.

#### Developement board used: STM32F429
#### Sensor used: Force Sensor,Resistance-type Thin Film Pressure Sensor,500g ZD10-100

### Circuit Diagram:
<img width="378" alt="image" src="https://user-images.githubusercontent.com/24549454/209992149-39e6132c-0586-4fb9-807b-fe8e5f4d97c8.png">

### Snapshot - Normal Breathing:
<img width="1473" alt="image" src="https://user-images.githubusercontent.com/24549454/209992546-3e0332a0-4cee-4fd4-94a1-2bd5f0914ade.png">

### Snapshot - Breathing Stopped Alert Generated:
<img width="1497" alt="image" src="https://user-images.githubusercontent.com/24549454/209992622-020890e9-fd5a-4a29-90a5-c8dde9e81d92.png">
