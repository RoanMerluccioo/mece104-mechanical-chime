# Mechanical Chime System – MECE-104

This project was completed as part of **MECE-104 (Engineering Design Tools)** at RIT during Fall 2025.  
Our team designed and built a mechanically actuated chime system controlled by an Arduino that can automatically play a short song(45 seconds).

This repository is shared for **portfolio purposes**.

---

## What this project is

The system consists of:
- A motor-driven carriage that moves side-to-side to align with different chimes  
- Limit switches that define hard end stops and allow repeatable positioning  
- Solenoids used to strike the chimes  
- An Arduino that controls motion, timing, and actuation  

Once started, the system homes itself and then plays a full sequence of notes over a fixed total time.

---

## What I worked on

This was a **group project**. My main contributions included:
- Writing the Arduino control logic for motor movement and solenoid actuation  
- Implementing homing using limit switches  
- Mapping physical chime positions to software logic  
- Tuning strike timing so notes sounded consistent  
- Assisting with CAD modeling and physical assembly  

---

## Control logic (high-level)

```text
home the carriage using a limit switch
loop through the note sequence:
    move to the note position
    strike the correct solenoid
    wait until the scheduled time
stop all motion



---
**Academic note:** This project was completed for a university course and is shared at a high level for portfolio purposes only.
