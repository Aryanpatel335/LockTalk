<p align="center">
  <img src="https://github.com/Aryanpatel335/LockTalk/assets/42017629/7a7451dd-616c-4226-9ddb-ff0abf3a72f3" width="222">
</p>

# LockTalk

**Android Mobile Application written in Java**

This application was made for SFWRENG 3A04, with 4 other group members.

# Project Demo Link:

[Project Demo](https://youtu.be/3CSwkFuFJS4)

# LockTalk Summary:

This project involved developing a secure chat application tailored for an organization that required highly confidential communication channels due to threats of corporate espionage. The application was developed using Java with the Android SDK in Android Studio, integrating Firebase for backend services. This solution aimed to ensure secure messaging through encryption and controlled key distribution, with a focus on authentication and privacy.

### Core Requirements

1. **Key Distribution Centre (KDC) Server**: Implemented a server that managed cryptographic keys. The KDC generated and distributed keys to authenticated users and frequently updated these keys.

2. **Authentication Protocol**: Utilized a mediated authentication protocol like Kerberos to ensure that all entities requesting keys were authorized to do so.

3. **Symmetric-key Cryptography**: Employed a strong symmetric-key crypto-system such as AES for encrypting and decrypting messages.

4. **Secure Chat Log Storage**: Maintained a secure log on the server containing details of all communications, including participant identifiers, timestamps, and the chat history.

### Unique Features

- **Geolocation Tracking**: To enhance security protocols, the application offered optional geolocation tracking for users during messages. This feature helped in verifying the physical location of the communicators, adding an extra layer of security verification.

- **Screenshot Protection**: To prevent data leakage, the application included a feature to block or alert attempts to take screenshots of sensitive information within the app.

### Technology Stack and Development Tools

- **Programming Language**: Java
- **Development Environment**: Android Studio
- **Backend Services**: Firebase, providing real-time database and authentication services.
- **Additional Libraries/Tools**: Included cryptographic libraries compatible with Java for enhanced security measures.


# Detailed Project Breakdown:

[Project Breakdown](https://github.com/Aryanpatel335/LockTalk/files/15211016/3A04_D4.pdf)


