# WlanRadar
WiFi Scanner and Analyzer
A powerful and intuitive Android tool designed to give you deep insights into the wireless networks around you.
WLANRadar is more than just a simple WiFi list viewer. Through detailed data presentation and graphical channel analysis, it empowers you to find the best channel, identify signal interference, view detailed device information, and become an indispensable tool for network enthusiasts and professionals alike.
Screenshots
(It is highly recommended to replace these placeholders with actual screenshots of your app.)
List View	Channel Graph	Powerful Filter
[Place screenshot of the list view here]	[Place screenshot of the 2.4/5 GHz graph here]	[Place screenshot of the filter dialog here]
Displays all available WiFi networks and their detailed information.	Visually represents channel occupancy to help you avoid congested channels.	Precisely filter the networks you want to see based on various criteria.
Key Features
Comprehensive Scanning: Scans and displays crucial information for surrounding WiFi networks, including:
SSID (Network Name) & BSSID (MAC Address)
Signal Strength (dBm) with intuitive color-coding (Green/Yellow/Red).
Frequency Bands (2.4 GHz, 5 GHz, 6 GHz, and even 60 GHz).
Channel & Channel Width (20/40/80/160 MHz).
WiFi Standard (ax, ac, n, etc.) (Requires Android 11+).
Security & Encryption (WPA3, WPA2, WEP, etc.).
Router Vendor (via OUI lookup).
Last Seen Timestamp.
Graphical Channel Analysis:
Provides separate channel graphs for the 2.4 GHz, 5 GHz, and 6 GHz bands.
Visualizes each network as a curve, where height represents signal strength and width represents the channel span, making it easy to spot interference.
Powerful Sorting & Filtering:
Sorting: Sort the network list by signal strength, channel, channel width, SSID, and more.
Filtering: A highly customizable filter lets you combine criteria like frequency band, SSID (contains), BSSID, channel, WiFi standard, and security. It even supports inverted matching.
Clean User Interface:
Features a modern, clean light theme with a focus on information clarity.
Offers a smooth and intuitive user experience for both list viewing and graph analysis.
Customizable Settings:
Allows users to adjust the WiFi scanning interval to balance information freshness and battery consumption.
Tech Stack
This project is built on the native Android stack, demonstrating a classic and robust application architecture.
Language: Java
Core Components: Android SDK, Fragment, ListView, ActionBar
Key Technologies:
Interacts with system services via WifiManager for WiFi scanning.
Builds professional channel analysis graphs from scratch using a custom View and the Canvas API.
Utilizes the Event Bus pattern for clean, decoupled component communication.
Includes a built-in OUI database for fast, offline BSSID-to-vendor lookups.
