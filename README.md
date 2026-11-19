# Awesome-Wearable-Computing-Health-Telemetry

# Top Wearable Computing & Health Telemetry Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Smartwatch Companion Apps, Biometric Telemetry Ingestion, Open Hardware Wearables, Workout Analytics & Self-Hosted Health Vaults*  
**Last updated: November 2026**

This repository (`Awesome-Wearable-Computing-Health-Telemetry`) tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Wearable Computing & Health Telemetry** — Top Wearable Computing Health Telemetry (Opensource) 🌟 Star if you like it! 🌟. These tools synchronize Bluetooth Low Energy (BLE) smartwatches and fitness bands, ingest continuous heart rate/HRV/SpO2/sleep telemetry, analyze endurance training loads, run open-source smartwatch firmwares, and store personal health metrics locally without vendor lock-in.

**Examples** include Apple Health, Google Fit / Health Connect, Garmin Connect, WHOOP, Oura Cloud, Fitbit, Polar Flow, Withings Health Mate, COROS Training Hub, Suunto App, and `inteliwear/sidepulse` (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for open-source Android/iOS wearable companion apps, open smartwatch firmwares, FIT/GPX/TCX telemetry parsers, self-hosted Apple Health / Garmin / Oura data aggregators, and DIY biometric sensors — ideal for quantified-self enthusiasts, sports scientists, embedded engineers, and privacy-focused developers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Apple Health & Fitness+](https://apple.com)**  
  On-device and iCloud-encrypted health telemetry hub aggregating Apple Watch vitals, ECG, sleep stages, workouts, and third-party HealthKit records.

- **[Google Health Connect & Google Fit](https://android.com)**  
  Android platform API and cloud ecosystem unifying health, sleep, and fitness telemetry across Wear OS watches and third-party wellness apps.

- **[Garmin Connect](https://garmin.com)**  
  Comprehensive cloud fitness and health telemetry platform syncing GPS activities, HRV status, Body Battery, sleep scores, and training readiness from Garmin wearables.

- **[WHOOP](https://whoop.com)**  
  Subscription wearable and cloud analytics platform tracking continuous heart rate variability (HRV), recovery, daily strain, and sleep coaching.

- **[Oura Cloud & Oura App](https://ouraring.com)**  
  Smart ring health telemetry platform delivering readiness scores, sleep architecture staging, skin temperature trends, and REST API webhooks.

- **[Fitbit (Google)](https://fitbit.com)**  
  Cloud health and activity tracking ecosystem monitoring daily steps, heart rate zones, sleep profiles, and stress management metrics.

- **[Polar Flow](https://polar.com)**  
  Sports science and training analytics web/mobile platform pairing with Polar watches and H10 chest straps for detailed cardiac and load telemetry.

- **[Withings App (formerly Health Mate)](https://withings.com)**  
  Connected health ecosystem aggregating hybrid smartwatch ECG/SpO2 metrics, smart scale body composition, and blood pressure monitor readings.

- **[COROS Training Hub](https://coros.com)**  
  Cloud endurance coaching and telemetry analysis portal visualizing EvoLab fitness metrics, GPS routes, and structured workout plans.

- **[Suunto App](https://suunto.com)**  
  Outdoor adventure and multisport wearable platform offering 3D route heatmaps, training load recovery analytics, and third-party sports integrations.

- **[Strava](https://strava.com)**  
  Social fitness tracking and GPS telemetry platform aggregating workouts from virtually all wearable hardware vendors with segment and power analytics.

- **[Terra API](https://tryterra.co)**  
  Unified cloud wearable telemetry API connecting developers to Garmin, Apple Health, Fitbit, Oura, WHOOP, Polar, and Suunto data streams.

## Open-Source GitHub Projects

- **[SidePulse (inteliwear/sidepulse)](https://github.com)**  
  Open-source wearable computing and continuous health telemetry project referenced in the seed list (`inteliwear/sidepulse`) for biometric data capture and wearable monitoring.

- **[Gadgetbridge (Freeyourgadget/Gadgetbridge)](https://codeberg.org)**  
  Flagship open-source Android companion app replacing proprietary vendor clouds for Pebble, Amazfit/Zepp, Xiaomi Mi Band, Garmin, Bangle.js, PineTime, Fossil, and Casio wearables completely offline.

- **[OpenScale (oliexdev/openScale)](https://github.com)**  
  Open-source Android health telemetry app supporting dozens of Bluetooth smart scales, blood pressure monitors, and body composition metrics with local SQLite storage and CSV export.

- **[InfiniTime (InfiniTimeOrg/InfiniTime)](https://github.com)**  
  Fast, modern open-source C++ firmware for the Pine64 PineTime smartwatch featuring heart rate monitoring, step counting, BLE notifications, and companion app sync.

- **[Bangle.js Firmware & App Loader (espruino/BangleApps)](https://github.com)**  
  Open-source JavaScript-programmable smartwatch firmware and modular app ecosystem supporting GPS, PPG heart rate, accelerometer telemetry, and Gadgetbridge integration.

- **[ZSWatch (ZSWatch/ZSWatch)](https://github.com)**  
  Open-source hardware and Zephyr RTOS-based smartwatch platform built on Nordic nRF5340 featuring BLE direction finding, sensor fusion, and Gadgetbridge compatibility.

- **[Open-Source Watch / Watchy (sqfmi/Watchy)](https://github.com)**  
  Open-source E-Ink smartwatch hardware and ESP32 firmware programmable in Arduino/ESP-IDF for ultra-low-power wearable telemetry and custom watchfaces.

- **[AsteroidOS (AsteroidOS/asteroid)](https://github.com)**  
  Open-source Linux distribution built with OpenEmbedded and Qt/Wayland designed for smartwatches, offering full root access, BLE sync, and sensor APIs.

- **[GoldenCheetah (GoldenCheetah/GoldenCheetah)](https://github.com)**  
  Open-source desktop performance analysis and physiological telemetry software for cyclists, runners, and triathletes parsing FIT, TCX, GPX, and HRV files locally.

- **[Intervals.icu / Runalyze Alternatives — FitTrackee (SamR1/FitTrackee)](https://github.com)**  
  Self-hosted open-source outdoor workout and GPS telemetry tracker built with Python and React for storing GPX tracks, heart rate charts, and personal records privately.

- **[Wanderer (Flomp/wanderer)](https://github.com)**  
  Self-hosted open-source trail database and GPS/wearable activity archive built with Go, SvelteKit, and PocketBase.

- **[Endurain (joaovitoriasilva/endurain)](https://github.com)**  
  Self-hosted open-source fitness tracking service written in Python and Vue that automatically syncs activities and health telemetry from Garmin Connect and Strava.

- **[HealthAutoExport / Apple Health Parser & Grafana Stack (krishnasrinivas/apple-health-grafana)](https://github.com)**  
  Open-source pipeline for parsing Apple Health XML/JSON exports into InfluxDB/PostgreSQL and visualizing heart rate, HRV, steps, and sleep trends in Grafana.

- **[GarminDB (tcgoetz/GarminDB)](https://github.com)**  
  Open-source Python toolset for downloading and parsing Garmin Connect monitoring data, FIT files, sleep, resting heart rate, and activities into local SQLite databases.

- **[python-garminconnect (cyberjunky/python-garminconnect)](https://github.com)**  
  Popular open-source Python API wrapper for programmatically retrieving biometric telemetry, HRV, sleep, body battery, and workouts from Garmin Connect.

- **[Open Wearables (the-momentum/open-wearables)](https://github.com)**  
  Self-hosted open-source unified wearable data platform and developer API aggregating telemetry across Garmin, Apple Health, Polar, Suunto, and WHOOP.

- **[HealthLog (MBombeck/HealthLog)](https://github.com)**  
  Self-hosted open-source quantified-self web app synchronizing Apple Health, Garmin, and Oura Ring metrics alongside blood pressure, glucose, sleep, and weight logs.

- **[OpenBCI GUI & BrainFlow (brainflow-dev/brainflow)](https://github.com)**  
  Open-source C++/Python/Rust biometric telemetry library for acquiring, filtering, and analyzing EEG, EMG, ECG, and PPG signals from wearable biosensors.

- **[HealthyPi (Protocentral/protocentral-healthypi-v5)](https://github.com)**  
  Open-source hardware and firmware vital-signs monitoring platform capturing clinical-grade ECG, respiration, PPG/SpO2, and body temperature telemetry.

- **[Sleep as Android / Sleepiness & HRV Toolkits — HeartPy (paulvangentcom/heartrate_analysis_python)](https://github.com)**  
  Open-source Python Heart Rate Variability (HRV) and PPG/ECG signal analysis toolkit designed for noisy wearable sensor data.

- **[NeuroKit2 (neuropsychology/NeuroKit)](https://github.com)**  
  Comprehensive open-source Python toolbox for neurophysiological and wearable biosignal processing (ECG, PPG, EDA, respiration, HRV, and actigraphy).

- **[Fitparse & Sweaty / fitdecode (polyvertex/fitdecode)](https://github.com)**
