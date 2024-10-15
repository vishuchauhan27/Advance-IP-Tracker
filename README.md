![DALL·E 2024-10-15 21 21 39 - A sleek and modern illustration of an IP Tracker tool interface on a computer screen  The interface should show an IP address being tracked, along wit](https://github.com/user-attachments/assets/99b2a498-4920-4d6f-b32c-7f2327c1ce94)

# 🚀 Advanced IP Tracker 📍

Welcome to **Advanced IP Tracker**! This is a powerful and user-friendly Bash script that helps you track detailed information about any IP address. Whether it's your own or someone else’s, this tool uses multiple public APIs to gather essential details such as geographical location, ISP, timezone, and even generates a Google Maps link for easy reference.

## 🌟 Features:
- **Track Your Own IP:** 
   - Provides your IP address, location, ISP details, ASN, and a Google Maps link with latitude and longitude.
- **Track Any IP:**
   - Enter a target IP address to retrieve the same level of detail, including the city, country, region, timezone, and more.
- **Visual Location Tracking:**
   - Get direct Google Maps links for any IP you track to see its exact location on the map. 🌍🗺️
- **Menu-Driven Interface:**
   - Simple and interactive interface for easy navigation and use.
   
## 🛠️ How to Use:
1. Clone the repository:
    ```bash
    git clone https://github.com/vishuchauhan27/advanced-ip-tracker.git
    cd advanced-ip-tracker
    ```
2. Make the script executable:
    ```bash
    chmod +x advanced-ip-tracker.sh
    ```
3. Run the script:
    ```bash
    ./advanced-ip-tracker.sh
    ```

## 📋 Menu Options:
1. **Check My IP**: Displays detailed information about your IP, such as:
   - IP Address
   - City, Region, Country
   - Latitude & Longitude
   - ISP & ASN
   - Google Maps link 🗺️

2. **Track Victim IP**: Input any IP address to retrieve:
   - IP Address
   - City, Region, Country
   - Timezone, Postal Code
   - ISP & ASN
   - Google Maps link 🌍

3. **Exit**: Exit the program.

## 🎯 API Services Used:
- [IP-API](http://ip-api.com): For location and ISP details.
- [IPAPI](https://ipapi.co): For geolocation data such as latitude, longitude, and more.

## 🚧 Prerequisites:
- **cURL** must be installed on your system to fetch data from the APIs:
    ```bash
    sudo apt-get install curl
    ```

## 📸 Screenshots:
- **Main Menu**
  
   ![2024-10-15_22-07](https://github.com/user-attachments/assets/e61eb2cf-b929-4010-ba61-a12e06a32c0c)
  
- **IP Tracking Result**  
   ![IP Tracking Result](https://example.com/ip-result.png)

## 🤝 Contributing:
Feel free to fork this repository and contribute by submitting a pull request. Any enhancements, bug fixes, or additional features are welcome!

---

Enjoy tracking IPs with **Advanced IP Tracker**! 🌍🔍
