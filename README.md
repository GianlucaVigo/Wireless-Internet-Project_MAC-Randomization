# Wireless Internet Polimi Course Project: Characterizing MAC Randomization

## Basic Info
This project was part of the evaluation for the Wireless Internet course at Polimi during the academic year 2023-24.
It was evaluated 4/4 so I hope it could be a quite good reference for future implementations.

## Project Description
Modern smartphones randomize their MAC address during probe request emission. 
You are requested to produce a dataset characterizing the MAC randomization of your own device, following what done in the following paper: “A dataset of labelled device Wi-Fi probe requests for MAC address de-randomiza6on” by L. Pintor and L. Aztori, Computer Networks, Vol. 205, March 2022. 
The project should output a set of .pcap files, containing probe requests emiXedfrom your smartphones in different condi6ons (screen on/off, Wi-Fi on/off, Power saving on/off) to characterize the randomization behaviour of your smartphone. 
A final report is required to describe your findings.

## Project Components
The project is characterized by three main elements
- PDF Report: it contains every aspect of the project implementation, from the Setup to the Results.
- Jupyter Notebook: it is the notebook, I designed for filtering and analysis operations.
- *Wireshrak Captures* Folder: it contains all the captures used as sources (both in .pcap and .pcapng versions)
