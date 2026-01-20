16-Bit Random Number Generator
Description

This project generates a 16-bit pseudo-random number using mouse cursor position, system time, and external data (Bitcoin price). These values are combined with bitwise operations to increase randomness.

Technologies

Python

pyautogui

time

requests

How It Works

The program mixes mouse coordinates, high-precision time, and API data using XOR and bit shifting. The final output is limited to 16 bits (0–65535).

If the API request fails, the system time is used as a fallback.

Usage

Install dependencies and run the script to generate random 16-bit numbers.

Note

This project is for educational purposes and is not cryptographically secure.
