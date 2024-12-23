### EGR 101 Blood Pressure Model

EGR 101 Project at Duke University, Fall Semester 2024

Team Members: Sarthak Agrawal, Anushka Sridhar, Charlotte Moore, Arielys Camille


Our client was Duke Ignite, a program that teaches a STEM curriculum to Durham middle schoolers. They were expanding their curriculum to include a blood pressure unit and tasked us with building a physical blood pressure model that would teach students how to take blood pressure, what the numbers in a blood pressure reading mean, and how different medical conditions (diabetes and heart disease) impact blood pressure readings.

Project was divided into 2 components: physical and electronic. Charlotte and Arielys focused on the physical aspects, creating the box to enclose the model and the model arm. Sarthak and Anushka focused on the electronics, with Sarthak taking the lead on hardware and Anushka taking the lead on software.

All the electronics are powered by an Arduino Leonardo, connected to a 12V power supply. The Arduino is connected to 3 input buttons (normal blood pressure, diabetes, and heart disease) which initiate the simulation. An LED strip in the arm starts the flow of blood when an input is chosen. The user is then given instructions on the LCD screen to pump up the pressure cuff to 180 mmHg and then release the pressure slowly. These pressure fluctuations are detected by a pressure sensor embedded in the arm which tells the user when to stop pumping the cuff. At this point, the systolic and diastolic values are displayed on the LCD. Throughout this process, the LED strip accurately depicts the flow of blood as it is when a blood pressure reading is taken. 

We went through processes of brainstorming, evaluating, prototyping, and testing multiple times before finalizing our design solution. The brainstorming and evaluating steps took 1 month and the prototyping and testing took 2 months. The final design solution has been given to Duke Ignite and they will use it to teach their blood pressure curriculum in Spring 2025.

Final prototype pictured below


![IMG_5357](https://github.com/user-attachments/assets/b36cca64-8e64-4cb3-a7de-2e6bf5cc457c)

Special thanks to: our professors Dr. Ann Saterbak and Dr. Michael Bergin for their constant support and guidance throughout the semester, our technical mentor Dr. Liz Feeney for teaching us the nuances of taking blood pressure measurements and for electronic help, and our client Dr. Megan Madonna who helped us understand the needs of Duke Ignite and sculpt the project into something that will be useful for the middle schoolers who will use it.
