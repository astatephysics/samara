# samara
Red Wolf Space Program's samara-style glider payload

----------------------------------------------------------
## Overview

Samara are a fruit with a fibrous wing-like structure that increases their wind-borne dispersal distances. Some of these like maple and ash seeds may slow their descent by autorotation as such they provide much entertainment for us humans who find them about. This project seeks to develop an airborne payload that mimic this behavior with a 3d printed airframe housing a radio antenna and this printed circuit board. 

This version of the board is contstrained to a 30.5mm x 30.5mm board and is inspired by "CricketSATs." This consists of a RP2040 microcontroller, BME280 temperature/humidity/pressure sensor, BNO055 inertial measurement unit, and RF95 LoRA radio. Several indicator leds are included as well as a surface mounted piezo buzzer. A STEMMA/Qwiic-compatable JST connector provides access to peripheral boards over I2C (e.g., GPS breakout board, realtime clocks, science payloads.)
