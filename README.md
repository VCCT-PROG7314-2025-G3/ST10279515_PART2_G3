# ST10279515_PART2_G3
# RideConnect

RideConnect is an Android-based carpooling and ride-sharing application designed to make commuting easier, more affordable, and more social.  
The app allows users to log in using *Google Single Sign-On (SSO)* or register manually using their *email and password*.  

Once logged in, users can view available rides, add a new ride, search for rides, message other users to coordinate travel logistics, and manage their profile and settings — all through a clean, intuitive interface.

---

###  Features

####  Authentication
- *Google Sign-In (SSO):* Secure and quick login using a Google account.  
- *Email & Password Registration:* Users can also register manually.

####  Home Screen
- Displays a list of *available rides* posted by users.  
- Allows users to *add their own ride* by entering trip details such as origin, destination, date, and time.

####  Search Screen
- Lets users *search for specific rides* based on pickup location, destination, driver name, or date.

####  Message Screen
- Built-in *messaging system* for smooth communication between drivers and passengers.

#### Profile Screen
- Enables users to *update personal details*, including name, contact number, and profile photo.

####  Settings Screen
- Allows users to *customize app settings* such as notifications, privacy, and account preferences.

---

###  Tech Stack

| Component | Technology |
|------------|-------------|
| *Frontend* | Android Studio (Java/Kotlin) |
| *Authentication* | Firebase Authentication (Google Sign-In + Email/Password) |
| *Backend API* | Node.js / Express (runs locally) |
| *Database* | Firebase Realtime Database / Firestore |
| *Messaging* | Firebase Cloud Messaging / Firestore Chat Collection |
| *UI Design* | Material Design Components |

---

### How It Works

1. *Login / Register*  
   Users can sign in with Google or create an account using email and password.  

2. *View or Add Rides*  
   The Home screen displays available rides and allows users to post new ones.  

3. *Search Rides*  
   The Search tab enables users to quickly find specific rides.  

4. *Communicate*  
   The Message screen allows real-time chat between drivers and passengers.  

5. *Manage Profile & Settings*  
   Users can edit their details and customize preferences anytime.

---
