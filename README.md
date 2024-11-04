# Raspberry-Pi-Display-Project
Overview
The goal of this project was to repurpose an old monitor and transform it into a smart display or magic mirror using a Raspberry Pi. This setup utilizes the Raspberry Pi Zero W2 to run DAKboard, a customizable smart display platform. The project is straightforward, providing a great use case for an old monitor while showcasing your ability to work with embedded systems and display customization.

Materials
To replicate this project, you will need the following items:

Old monitor (preferably with an HDMI input)
Raspberry Pi Zero W2 (or any other Raspberry Pi model)
MicroSD card (at least 8GB recommended)
HDMI cord
Micro-HDMI to HDMI converter (for Raspberry Pi Zero models)
Power supply for the Raspberry Pi
Laptop or PC with an SD card reader
Software Requirements
Raspberry Pi Imager: Download from Raspberry Pi's website
DAKboard OS: Available via Raspberry Pi Imager in the "Other specific purpose OS" section
DAKboard Account: Set up on the DAKboard website to customize the display
Setup and Configuration
Step 1: Preparing the SD Card
Download and install the Raspberry Pi Imager on your laptop or PC.
Insert the microSD card into your computer's SD card reader.
Open the Raspberry Pi Imager and select the following:
Operating System: Navigate to Other specific purpose OS and choose DAKboard.
Storage: Select your microSD card as the storage destination.
Raspberry Pi Model: Confirm you're using a Raspberry Pi Zero W2, or select the correct model for your setup.
Click "Write" to install the DAKboard OS onto your SD card.
Step 2: Connecting the Hardware
Insert the microSD card into the Raspberry Pi.
Connect the HDMI cord between the monitor and the Raspberry Pi, using the micro-HDMI to HDMI converter if necessary.
Power up the monitor and connect the Raspberry Pi to a power source using its power supply.
Step 3: Setting up DAKboard
Once powered up, DAKboard should automatically boot on the monitor.
On the first boot, a QR code and IP address will appear on the screen. Use either of these to connect the Raspberry Pi to your Wi-Fi network.
Option 1: Scan the QR code with your phone.
Option 2: Enter the IP address into a browser on your computer to access the Raspberry Pi remotely.
Go to the DAKboard website and create an account to start customizing your display.
Step 4: Customizing the Display
Use your DAKboard account to adjust the screen layout, add widgets, display information such as weather, time, calendar events, or even use it as a photo frame.
Save your custom settings, and DAKboard will automatically update the Raspberry Pi display.
Challenges and Solutions
Wi-Fi Connectivity: Ensure that you either scan the QR code or manually enter the IP address correctly to connect the Raspberry Pi to Wi-Fi. If you experience issues, reboot the Raspberry Pi or check your network settings.
Results
Once the setup is complete, you have a fully functional smart display that can showcase dynamic information such as weather, calendar events, news feeds, or photos. DAKboard provides a user-friendly platform for customizing the content displayed on your repurposed monitor.

Future Improvements
Integrating additional smart display features, such as voice control or real-time data streams.
Expanding the functionality by adding custom Raspberry Pi scripts to pull in additional data or use the display for other purposes.
Housing the Raspberry Pi and monitor in a custom-built frame for a sleek, finished look.
Conclusion
This project offers an excellent way to give an old monitor new life, creating a functional and customizable smart display using simple hardware and software. The Raspberry Pi Zero W2 and DAKboard make the process easy and intuitive, offering countless possibilities for expanding or enhancing the display in the future.
