# Digital-clock
# 📌 Overview
This project presents a digital clock designed using logic gates and integrated circuits (ICs). The clock accurately displays time (hours, minutes, and seconds) and includes functionality for accelerated time counting via control buttons.

Two versions of the project have been implemented:

Without IC 4026 – Uses separate decade counters and decoders.

With IC 4026 – A more efficient design integrating counting and decoding.

# 🛠️ Tools & Components Used
# Version 1: Without IC 4026
IC 555 – Generates clock pulses.
IC 7490 – Decade counters for seconds and minutes.
IC 7448 – Decodes the count for 7-segment display.
Logic Gates – AND and NOT gates for reset operation.
7-Segment Displays – Visual representation of time.
Push Buttons – Accelerates time counting.
# Version 2: With IC 4026
Crystal Oscillator – Generates precise clock pulses.
IC 4026 – Combines counting and decoding for display.
JK Flip-Flop – AM/PM indication using LEDs.
NAND Gate – Manages reset functionality.
Push Buttons – Accelerates time counting.
# ⚙️ Working Mechanism
# 1️⃣ Clock Pulse Generation
IC 555 (Version 1) or Crystal Oscillator (Version 2) generates clock pulses.
Push buttons increase the clock speed for testing.
# 2️⃣ Counting & Display
IC 7490 (Version 1) or IC 4026 (Version 2) count pulses and update the display.
Each counter resets at predefined values (seconds: 60, minutes: 60, hours: 12/24).
# 3️⃣ AM/PM Indication (Version 2)
JK Flip-Flop toggles every 12 hours.
Two LEDs indicate AM or PM mode.
# 4️⃣ Reset Operation
AND & NOT gates (Version 1) or NAND gates (Version 2) reset counters at the correct time intervals.
# 🚀 Features
✔ Displays hours, minutes, and seconds accurately
✔ Push-button control for accelerated counting
✔ AM/PM Indication (Version 2 only)
✔ Modular design using basic digital electronics

# 📂 Project Files
Report LogicDesign Project.pdf – Full documentation of the project.
With_Bonus.pdsprj – Project design files.
# 🔧 How to Run
Assemble the circuit on a breadboard or simulate it using software.
Provide power and observe the time counting.
Use the push button to accelerate counting for testing.
(Version 2) Observe the AM/PM LED toggling every 12 hours.
