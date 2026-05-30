🔎 What is this software?
	•	GNSS (Global Navigation Satellite System): GPS, GLONASS, Galileo, etc. are examples.
	•	This software is used to record GNSS signals (satellite navigation signals) and then replay them for testing purposes.
	•	It works with hardware like AD9361 SDR (Software Defined Radio) to capture and transmit GNSS signals.
	•	Engineers use it to test navigation devices, simulate GPS environments, and debug GNSS-based applications without needing live satellite signals.

⸻

🖥️ Software Tabs and Functions
	1.	Connect
	•	Choose COM port and baudrate to connect to the GNSS hardware (AD9361, RTCM).
	•	Select number of channels (Single/Dual).
	•	Choose reference frequency (e.g., 40 MHz External).
	•	After submitting, it shows “Connected to COM4 with Baudrate 115200 for AD9361”.
	2.	Record
	•	Used to record live GNSS signals.
	•	Options include:
	•	Folder to save data.
	•	Select Rx1 / Rx2 channels.
	•	LO frequency (signal frequency).
	•	ADC bits (signal resolution).
	•	Bandwidth/Gain.
	•	Sampling frequency.
	•	File name & duration.
	•	Shows progress bar and available SSD space.
	3.	Replay
	•	Used to replay previously recorded GNSS signals.
	•	Options include:
	•	Select file (AD9361 / RTCM).
	•	Set Gain (dB).
	•	RTCM rate (Hz).
	•	Start time & run time.
	•	Auto-replay mode.
	•	Useful for reproducing real GNSS conditions in the lab.
	4.	Files
	•	Manage recorded files stored in NVMe SSD.
	•	Lets you browse, select, or remove GNSS data files.
	•	Displays SSD label and available files.
	5.	About
	•	Shows software version (e.g., Version 1.60).
	•	Provides User Manual and info about the tool.

⸻

⚡ Typical Use Case
	•	A researcher wants to test a GPS receiver:
	1.	Record satellite signals from a real location.
	2.	Replay them later in the lab to check how the GPS device behaves.
	3.	No need to go outdoors every time → saves time, repeatable results.

⸻

✅ In short:
This is a GNSS testing tool that helps record satellite navigation signals, store them, and replay them for simulation, debugging, or research.


<img width="565" height="515" alt="Screenshot 2025-08-24 at 1 48 52 PM" src="https://github.com/user-attachments/assets/b5687afd-876e-4c32-b821-bfb401b88fc0" />










