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





<img width="565" height="516" alt="Screenshot 2025-08-24 at 1 49 08 PM" src="https://github.com/user-attachments/assets/82273b25-a258-4691-aa42-9e5dc78791dc" />
<img width="564" height="517" alt="Screenshot 2025-08-24 at 1 49 00 PM" src="https://github.com/user-attachments/assets/a097e3d8-d665-4cae-9fbb-53b86511763c" />
<img width="565" height="515" alt="Screenshot 2025-08-24 at 1 48 52 PM" src="https://github.com/user-attachments/assets/39b0d6e5-2bcb-43c3-9560-5293f0557fe7" />
<img width="564" height="514" alt="Screenshot 2025-08-24 at 1 48 35 PM" src="https://github.com/user-attachments/assets/53e7204f-f19e-4d87-bc5a-3cdeed680fc9" />
<img width="564" height="516" alt="Screenshot 2025-08-24 at 1 36 53 PM" src="https://github.com/user-attachments/assets/d6e7b2d5-432c-412d-bd58-4131afd5c3f2" />
<img width="567" height="517" alt="Screenshot 2025-08-24 at 1 36 33 PM" src="https://github.com/user-attachments/assets/ed9da0ff-875f-4f7f-b49a-3664f3572db3" />




