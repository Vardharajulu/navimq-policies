# Privacy Policy

This privacy policy applies to the **NaviMQ** app (hereby referred to as "Application") for mobile devices that was created by **Vardharajulu K N** (hereby referred to as "Service Provider") as an **Ad Supported** service. This service is intended for use "AS IS".

### Information Collection and Use
The Application collects information when you download and use it. This information may include:
* Your device's Internet Protocol address (IP address).
* Operating system and device identifiers (Advertising IDs).
* Any information you explicitly provide within the application, such as configuration settings, user subscribe and publish data.
* Third-Party Data Collection: The Application utilizes integrated third-party SDKs (such as AdMob) that automatically collect device identifiers, operating system details, and approximate geographical location to provide analytics and personalized advertising. For more details, please refer to the "Third-Party Access" section.

### Local Data Security (Hashed & Encrypted)
Aside from advertising data handled by AdMob, all user-provided configuration data is stored locally on the device with the following security measures:
* **Hashed Passwords:** MQTT broker passwords are **cryptographically hashed** before being stored in the database. Because hashing is a one-way process, the original password cannot be retrieved or recovered by the Service Provider or any third party.
* **User Authentication:** Due to the security of hashing, users must provide their password for setup session/re-authentication as required by the broker.
* **Encrypted Database:** All other configuration data is stored in an **encrypted local database** on the device to prevent unauthorized access.
* **Zero Server Access:** The Service Provider does not collect, store, or have access to any data stored in this local database.

### MQTT Connectivity & User Responsibility
The Application acts as a tool for communication between the user and their chosen MQTT broker.
* **Hostname & URL:** Users are solely responsible for the hostnames, URLs, and ports they provide within the Application. The Service Provider has no control over the destination or security of these external servers.
* **Data Communication:** Any data sent to a hostname provided by the user is the user's responsibility. The Service Provider does not monitor or gather any data transmitted during these sessions.

### MQTT Data Transmission (Protocol Disclosure)
* **Non-TLS Transmission:** If a user connects to a broker without enabling TLS/SSL, the Application transmits data (including messages and credentials) in **raw, plain-text format**.
* **Protocol Risks:** The user acknowledges that using unencrypted protocols carries inherent risks. The Service Provider is not liable for data intercepted during transmission to the user-defined hostname.

### Third-Party Access & Data Transmission
The Application interacts with external services in the following ways:
1. **Advertising (AdMob):** The Application uses **[Google AdMob](https://admob.google.com/home/)** to serve advertisements. AdMob may collect and use Device IDs and Advertising IDs via secure HTTPS to personalize ads and analyze performance.
    * **Policy Requirement:** By using this Application, you acknowledge and agree to be bound by the **[Google AdMob Privacy Policy](https://support.google.com/admob/answer/6128543?hl=en)**. Users are encouraged to read this policy to understand how Google manages ad-related data.
2. **User-Provided MQTT Brokers:** The Application transmits credentials and message payloads directly to the **MQTT Broker hostname/URL** provided by the user. 
    * **User Responsibility:** These brokers are third-party services not controlled by the Service Provider. Users are responsible for the security practices of the brokers they choose to connect to.

### Data Retention
The Service Provider does not collect, store, or transmit any user data to personal or private servers. 
* **Local Autonomy:** All data, configurations, and messages remain on your device within an encrypted local database.
* **Automatic Deletion:** Since all data is stored locally, it is automatically purged by the Android Operating System when the Application is uninstalled. 

### Opt-Out Rights
You can stop all collection of information by the Application easily by uninstalling it. You may use the standard uninstall processes as may be available as part of your mobile device or via the mobile application marketplace or network.

### Children
The Service Provider does not knowingly collect information from children under 13. Since MQTT configurations are stored locally and encrypted, no personal data from children is gathered by the Service Provider.

### Changes
This Privacy Policy may be updated from time to time. The Service Provider will notify you of any changes to the Privacy Policy by updating this page with the new Privacy Policy. You are advised to consult this Privacy Policy regularly for any changes, as continued use is deemed approval of all changes.

**Effective Date:** 2026-01-28

### Contact Us
If you have questions regarding the local hashing, encryption, or privacy practices, please contact **raajulu@gmail.com**.

---

By using NaviMQ Application, you agree to this Privacy Policy.
