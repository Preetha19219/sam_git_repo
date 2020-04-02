1. What would an embedded system have to boot? 

 Steps before the boot sequence: 
	* Power ON
	* Reset to processor until good power supply is available.
	* Reset nagated, processor-ready, points to ROM address

 Boot sequence:
	* Power ON Self Test
	* Looks for video card, runs build in BIOS program 
	* System BIOS looks for other peripheral BIOS, executes other BIOS
	* BIOS displays start-up screen
	* Memory-count test, hard-disk-drive-parameter setting
	* BIOS looks for COM and LTP ports
	* BIOS looks for boot-sequence setting
	* Loads operating system
	* BIOS copies files to memory, operaring system takes over boot-up
	* Operating system checks system memory, loads drivers and starts application

2. What would an IOT device need?

	*IoT சாதனங்களில்  ireless sensors, software, actuators, and computer devices ஆகியவை அடங்கும். அவை இணையம் வழியாக செயல்படும் ஒரு குறிப்பிட்ட பொருளுடன் இணைக்கப்பட்டுள்ளன, மனித தலையீடு இல்லாமல் தானாகவே பொருள்கள் அல்லது மக்களிடையே தரவை மாற்ற உதவுகிறது.





