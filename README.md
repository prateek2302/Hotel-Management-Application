**Hotel Management Application**

------------------------

Welcome to Hotel Management Application. The Wild Oasis is a user friendly hotel management application. This application is designed to manage hotel operations,
including sales statistics, cabin management, user management, booking management and various customization options. It integrates authentication, database storage, and dark mode
features. And so much more!.

The purpose of my project is to implement my advanced JavaScript, TypeScript and Database Query skills in a web application. Moreover my futher enhance my knowledge of ReactJS.

------------------------------------------------------------------------------------------------------------------------------------------------

⭐️Demo Account:


Username: admin@example.com

Password: admin@example

-----------------------------------------------

💫Key Features:
-----------------------------------------------
****Authentication and Authorization****

Users of the app are hotel employees. They can logged in into the application to perform tasks.
New users can only be signed up inside the applications (to guarantee that only actual hotel employees can get accounts).
Users able to upload an avatar, and change their name and password

****Cabins****

The app has a table view with all cabins, showing the cabin photo, name, capacity, price, and current discount.
Users able to update or delete a cabin, and create new cabins (including uploading a photo)

****Bookings****

The app has a table view with all bookings, showing arrival and departure dates, status, and paid amount, as well as cabin and guest data.
The booking status can "unconfirmed" (booked but not yet checked in), "checked in", or "checked out". The table filterable by this important status.
Other booking data includes: the number of guests, number of nights, guest observations, whether they booked breakfast, breakfast price.

****Check-in/Check-out****

Users able to delete, check-in, or check out a booking as the guest arrives (no editing necessary for now).
Bookings may not have been paid yet on guest arrival. Therefore, on check-in, users need to accept payment (outside the app), and then confirm that payment has been received (inside the app).
On check-in, the guest should have the ability to add breakfast for the entire stay, if they hadn't already.

****Guests****

Guest data contain full name, email, national ID, nationality, and a country flag for easy identification.

****Dashboard****

The initial app screen should be a dashboard, to display important information for the last 7, 30, or 90 days:
A list of guests checking in and out on the current day. Users should be able to perform these tasks from here.
Statistics on recent bookings, sales, check-ins, and occupancy rate.
A chart showing all daily hotel sales, showing both "total" sales and "extras" sales (only breakfast at the moment).
A chart showing statistics on stay durations, as this is an important metric for the hotel

****Settings****

Users able to define a few application-wide settings: breakfast price, min and max nights/booking, max guests/booking.



-------------------------------------------------------

💫 Demonstration

Login Page:
![IMG_2139](https://github.com/user-attachments/assets/73c075f1-b3cf-44ad-901d-7a5baa7b61a2)

Dashboard:
![IMG_2140](https://github.com/user-attachments/assets/a9ba28b1-57c6-4fcd-ac38-8ac7dcafd47d)

Dark Preview Theme:
<img width="1395" alt="Screenshot 2025-03-11 at 01 42 35" src="https://github.com/user-attachments/assets/a632ab2d-0d77-490e-b862-4f8b282889b9" />

------------------------------------------------------

Technologies Used:

1. React
2. Supabase
3. @tanstack/react-query
4. data-fns
5. react-router-dom
6. recharts
7. styled components
8. react-hot-toast
9. react-icons
10. react-hook-forms

---------------------------------------------------------

Installation Steps:


1.Install the required dependencies:  npm install


2.Start the development server:  npm run dev


3.Access the application at:  http://localhost:5173 or Your Local URL



--------------------------------------------------------------
