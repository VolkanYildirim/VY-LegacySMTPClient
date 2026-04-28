# 📧 VY-LegacySMTPClient

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Network](https://img.shields.io/badge/Protocol-SMTP-lightgrey?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Legacy_Code-blue?style=for-the-badge)


A Windows Forms desktop utility built with C# for sending emails via Google's SMTP servers. This legacy project demonstrates basic network protocol usage, SMTP client configuration, and GUI-based data handling from the early stages of my software development journey.

### ⚠️ Security & Architecture Note (Basic Auth Deprecation)
This version of the application relies on **Basic Authentication** (raw username and password transmission). Modern secure email providers, including Google, have deprecated this authentication model in favor of "Zero Trust" protocols like **OAuth2** or dedicated App Passwords to prevent credential harvesting. 

As a result, running this application with standard credentials will currently trigger authentication blocks by the provider. This repository is maintained as a historical baseline for a planned DevSecOps refactoring loop to implement modern, token-based secure authentication.
