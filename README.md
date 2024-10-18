Contact App
This is a simple and efficient Contact Management App built using React (Vite), JavaScript, Tailwind CSS, and Firebase for the backend.

Features
Add Contacts: Manually add new contacts to the app.
Update Contacts: Modify details of existing contacts.
Delete Contacts: Remove unwanted contacts from the list.
Real-time Updates: All data operations are managed through Firebase, ensuring real-time updates.
Responsive Design: The app is fully responsive, providing a smooth experience across devices.


Tech Stack

Frontend:
React (Vite)
JavaScript
Tailwind CSS

Backend:
Firebase (Real-time Database)

Installation
Clone the repository:
git clone https://github.com/yourusername/contact-app.git
cd contact-app

Install dependencies:
npm install


Set up Firebase:

Create a Firebase project and enable Firestore or Realtime Database.
Copy your Firebase config and add it to firebase.js in the config folder.

Run the app:
npm run dev

Usage
On the home page, you can view the list of contacts.
To add a contact, click the "Add Contact" button, fill in the form, and submit.
To update or delete a contact, click on the contact card and choose the desired action.

Folder Structure
/src – Contains all the main components and logic.
/components – Contact form, contact card, and additional UI elements.
/config – Firebase configuration.
/hooks – Custom React hooks for managing contact data.
/public – Contains static assets.
/firebase.js – Firebase initialization and connection to the database.



