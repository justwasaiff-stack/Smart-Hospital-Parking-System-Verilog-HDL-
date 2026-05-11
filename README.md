The Smart Hospital Parking System is a digital logic design project developed to automate and optimize parking management within a hospital environment. Using Verilog HDL, the system focuses on maximizing efficiency by prioritizing emergency vehicles and organizing parking spaces for different user categories, such as staff and patients.  
Key Features & Logic 🧠
The system is designed to handle real-world hospital scenarios through hardware-level automation:
• Priority Management: The system is programmed to prioritize ambulances, ensuring immediate access to parking spots during emergencies.  
• Dual-Zone Capacity Tracking: It manages two separate parking zones: one for Hospital Staff and another for Patients/Visitors.  
• Automated Entry/Exit Control: Gates are controlled based on current occupancy and the type of vehicle entering.  
• Availability Indicators: Provides real-time signals when the parking lot is full or has available spots for specific categories.  
Technical Implementation 🛠️
• Language: Verilog Hardware Description Language (HDL).  
• Design Methodology: The system uses counters for tracking vehicles and comparators for priority logic, ensuring a robust and reliable controller.  
• Core Logic: Focuses on Finite State Machine (FSM) principles to manage transitions between entry, validation, and parking states.
How it Works ⚙️
1. Detection: Sensors detect the vehicle type at the entrance.
2. Prioritization: If an ambulance is detected, it is given immediate priority over other vehicles.
3. Validation: For regular vehicles, the system checks the availability in the designated zone (Staff or Patient).
4. Access: The gate opens only if space is available, and the internal counter is updated.
