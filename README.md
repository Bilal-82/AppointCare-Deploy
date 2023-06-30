# AppointCare
AppointCare is a user-friendly web application designed to streamline the process of scheduling appointments with doctors. Whether you're a patient in need of medical assistance or a healthcare professional looking to manage your appointments efficiently, AppointCare is here to simplify the entire experience.<br/>

For Patients: With AppointCare, patients can easily find and book appointments with doctors in their area. The app provides a comprehensive database of healthcare providers, including general practitioners, specialists, and other medical professionals. Users can search for doctors based on their specialization, location and availability ensuring they find the right healthcare provider for their specific needs. Once a suitable doctor is found, AppointCare allows patients to view the doctor's profile, which includes information about their qualifications, experience, and fees per consaltation. This helps patients make an informed decision when selecting a healthcare professional. Once a doctor is chosen, users can book an appointment directly through the app, selecting a convenient date and time slot.<br/>

For Doctors: AppointCare recognizes the importance of a seamless appointment management system for healthcare providers. Doctors can register and create their profiles within the app, showcasing their areas of expertise, qualifications, and professional achievements. By joining the AppointCare network, doctors can expand their patient base and reach a wider audience. Once registered, doctors can manage their schedules efficiently through the app. They have the flexibility to update their availability, block specific time slots, and specify appointment durations. AppointCare's intelligent scheduling algorithm optimizes the doctor's calendar, reducing the likelihood of appointment conflicts and ensuring an organized workflow.<br/>


# TOOLS & TECHNOLOGY USED
⚛️ React.js<br/>
💚 Node.js<br/>
🛣️ Express.js<br/>
🔐 JsonWebToken ( For Authentication)<br/> 
 HTML <br/>
 CSS <br/>
 BootStrap<br/>
 Concurrently<br/>
 AntDesign <br/>
 Redux<br/> 
 Mongoose<br/>
 Nodemon<br/>

# DATABASE USED
🍃 MongoDB<br/>

# LICENSE
MIT<br/>

# Features
The System consists of three types of Users:<br/>
Admin<br/>
Patient<br/>
Doctor<br/>

Admins: They control all the activities and accept/reject Doctors.<br/>
Patient: They are the driving users of the application who book appointment with the doctors.<br/>
Doctor: They are responsible for providing their time slot to their patient.<br/>
Register, login and logout functionalities.<br/>
# 🙂 Doctor Features:
Doctor submit requests to display their profile on the homepage along with some basic information.<br/>
Appointment requests by patient for doctor can be approved or rejected by the respective doctor, and they can simply monitor the features.<br/>
Doctors are able to examine their currently appointment request and they can approved and reject the request (if any).<br/>
Doctor can update their profile.<br/>
# 🤠 Admin Features:
Admin receive all the requests made by doctors.<br/>
Admin can accept or block the doctor requests depending upon the details provided by a doctor.<br/>
Admin can view all the pending doctor's application.<br/>
Admin can also view all the users (Patients & Doctors) in the application.<br/>
Admin will recieve notification for new request of doctors.<br/>
# 🫡 Patient Features:
Patient can book appointment from all the available doctors listed on homepage.<br/>
Patient will receive notifications from doctor about the status of their appointment.<br/>
Agents can mark their collection upon collection of food from donor's home.<br/>
Agents can also view all those appointments which have been booked by them previously.<br/>

# Live Demo
[AppointCare](https://appointcare.onrender.com/login)

# For Testing Purpose
Use email:- admin@admin || Password:- 12345.<br/>
New user can register for user's feature.<br/>
New user can apply as doctor and accept their application by logging in with admin credential(point-1) to accept the request and then login to see the doctos's features.<br/>
