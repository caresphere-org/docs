# HOSPITAL MANAGEMENT SYSTEM

## Backend
### Springboot 
https://start.spring.io/

1. MySQL driver
2. Spring data JPA
3. Spring web
4. Spring devtools
5. Lombok

## Frontend

### Resources
- https://v5.mantine.dev/guides/cra/
- https://v3.tailwindcss.com/docs/guides/create-react-app 



### User management  
  * **Admin features**  
    * CRUD users (doctors, nurses, patients, staff)  
    * Role-based access control and permission  
  * **Doctor features**  
    * Manage schedules and appointments  
    * Access patient medical records  
  * **Patient features**  
    * View personal medical records & appointment history  
    * Book, reschedule and cancel appointments

---

### Patient management  
  * **Patient registration**  
    * Details \- demographics, insurance, emergency contact info  
  * **Medical records**  
    * Maintain patient history, diagnosis & treatment plans  
    * Upload and manage test reports & prescriptions

---

### Appointment scheduling  
  * **Booking system**  
    * Calendar view with slot availability for doctors  
    * Appointment status \- SCHEDULED, COMPLETED, CANCELLED  
  * **Doctor availability**  
    * Manage doctor working hour and time slot

---

### Billing and invoicing  
  * **Invoice generation**  
    * Generate bills for treatments, consultation & tests  
    * Integrate 3rd party payment gateway  
  * **Payment tracking**  
    * Manage patient payment history and dues

---

### Reporting and analysis  
  * **Dashboard overview**  
    * Visualize hospital operations \- revenue, appointments, patient count.  
    * Filter data time range, department or doctor  
  * **Custom report**  
    * Generate reports for staff performance, resource utilization & patient outcomes

---

### Pharmacy management  
  * **Inventory tracking**  
    * Manage stock levels for medicines & equipments  
    * Notify low-stock & expiry (kafka)	  
  * **Prescription integration**  
    * Link prescriptions to patient records & orders

---

### Laboratory management  
  * **Test management**  
    * Track test requests, results & payments  
  * **Integration with records**  
    * Upload test results directly to patient records

---

### Notification & communication
  * **Email & SMS notification**  
    * Alerts for appointments, billing & health updates  
  * **Real-time chat**  
    * Facilitate communication between patients & hospital staff

---

### Optional features

* Notification system & remainder using Kafka  
* Chat and messages system using websocket

---

---

## Non-functional requirements

### Performance
  * Use server-side rendering \- for faster page load  
  * Optimize db queries for scalability  
### Security  
  * JWT authentication & data encryption  
### Responsive design  
  * Ensure compatibility across devices (mobile, tablet, desktop)

---

## Tools and Libraries
### Frontend (React \+ Tailwind)

* Component library: Mantine & PrimeReact for UI components  
* Icons: Tabler Icons & Heroicons for a modern aesthetic  
* Styling: Tailwind CSS for rapid styling & responsive design

### Backend (Springboot)

* Framework \- SB  
* DB \- MySQL for patient record & system data  
* Authentication: JWT

### State management

* Redux: to manage global states like user sessions & UI states

### Additional libraries

**Data visualization:** Nivo & Apex charts for analytics

