# AppointCare-Deploy
AppointCare is a user-friendly web application designed to streamline the process of scheduling appointments with doctors. Whether you're a patient in need of medical assistance or a healthcare professional looking to manage your appointments efficiently, AppointCare is here to simplify the entire experience.

For Patients: With AppointCare, patients can easily find and book appointments with doctors in their area. The app provides a comprehensive database of healthcare providers, including general practitioners, specialists, and other medical professionals. Users can search for doctors based on their specialization, location and availability ensuring they find the right healthcare provider for their specific needs. Once a suitable doctor is found, AppointCare allows patients to view the doctor's profile, which includes information about their qualifications, experience, and fees per consaltation. This helps patients make an informed decision when selecting a healthcare professional. Once a doctor is chosen, users can book an appointment directly through the app, selecting a convenient date and time slot.

For Doctors: AppointCare recognizes the importance of a seamless appointment management system for healthcare providers. Doctors can register and create their profiles within the app, showcasing their areas of expertise, qualifications, and professional achievements. By joining the AppointCare network, doctors can expand their patient base and reach a wider audience. Once registered, doctors can manage their schedules efficiently through the app. They have the flexibility to update their availability, block specific time slots, and specify appointment durations. AppointCare's intelligent scheduling algorithm optimizes the doctor's calendar, reducing the likelihood of appointment conflicts and ensuring an organized workflow.

# TOOLS & TECHNOLOGY USED
⚛️ React.js
💚 Node.js
🛣️ Express.js
🔐 JsonWebToken ( For Authentication) 
 HTML 
 CSS 
 BootStrap
 Concurrently
 AntDesign 
 Redux 
 Mongoose
 Nodemon

# DATABASE USED
🍃 MongoDB

# LICENSE
MIT

# Features
The System consists of three types of Users:
Admin
Patient
Doctor

Admins: They control all the activities and accept/reject Doctors.
Patient: They are the driving users of the application who book appointment with the doctors.
Doctor: They are responsible for providing their time slot to their patient.
Register, login and logout functionalities.
# 🙂 Doctor Features:
Doctor submit requests to display their profile on the homepage along with some basic information.
Appointment requests by patient for doctor can be approved or rejected by the respective doctor, and they can simply monitor the features.
Doctors are able to examine their currently appointment request and they can approved and reject the request (if any).
Doctor can update their profile.
# 🤠 Admin Features:
Admin receive all the requests made by doctors.
Admin can accept or block the doctor requests depending upon the details provided by a doctor.
Admin can view all the pending doctor's application.
Admin can also view all the users (Patients & Doctors) in the application.
Admin will recieve notification for new request of doctors 
# 🫡 Patient Features:
Patient can book appointment from all the available doctors listed on homepage.
Patient will receive notifications from doctor about the status of their appointment.
Agents can mark their collection upon collection of food from donor's home.
Agents can also view all those appointments which have been booked by them previously.

# For Testing Purpose
Use email:- admin@admin || Password:- 12345.
New user can register for user's feature.
New user can apply as doctor and accept their application by logging in with admin credential(point-1) to accept the request and then login to see the doctos's features.
