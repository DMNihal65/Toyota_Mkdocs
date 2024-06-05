# Project Overview: Manufacturing Data Management for Toyota Maintenance

## **Introduction**

The Manufacturing Data Management (MDM) system is designed to streamline and enhance the maintenance operations for Toyota's two plants: TNGA and GD. This software solution provides comprehensive tools for monitoring, analyzing, and managing the state of various machines, spare parts, and production lines within these plants. By offering real-time data visualization, alarm monitoring, spare part management, and detailed analytics, the MDM system aims to improve operational efficiency, reduce downtime, and facilitate proactive maintenance.

##  **Project Requirements**



### **Functional Requirements**

### Machine State Monitoring
    
1. Display the current states of machines, axes, production lines, and parameter groups.

1. Provide real-time visualization of machine parameters.

1. Highlight critical, warning, and normal states with color-coded indicators.
   
 
### Real-Time Data Visualization
    
1. Show real-time graphs for both static and dynamic parameters.

1. Allow users to query data for specific time ranges and parameters.

1. Provide tools to set and adjust warning and critical limits for parameters.

### Alarm Monitoring
    
1. Maintain a table of alarms for selected machines over specified time ranges.

1. Generate Pareto charts for alarm counts and timespans.

1. Provide pie charts to visualize alarm timespans.


### Spare Part Management
    
1. Display machine-specific spare part details, including part counts and limits.

1. Allow users to add, delete, and reset spare parts.

1. Enable setting warning and critical limits for spare parts.


### Special Purpose Machines (SPM) Management
    
1. Manage SPM machine details and parameter states.

1. Display real-time graphs for static and dynamic parameters.

1. Allow position-based queries for laser cladding processes.



### Analytics
    
1. Provide machine analytics to track abnormalities over time.
1. Offer maintenance analytics to monitor operator-managed abnormalities.
1. Enable parameter analytics to evaluate specific machine parameters.



### User Management
    
1. Register new users with specific roles (Admin, Maintenance, User).
1. Ensure secure user management with restrictions on deleting the admin user.




### **Non-Functional Requirements**

1. **Scalability**
   - The system should handle increasing amounts of data and users without performance degradation.

2. **Reliability**
   - Ensure high availability and minimal downtime, especially during critical operations.

3. **Usability**
   - Design an intuitive and user-friendly interface to facilitate ease of use and reduce training time.

4. **Security**
   - Implement robust security measures to protect sensitive data and ensure user authentication and authorization.

## Project Features

### Machine State Monitoring
- **Comprehensive Status Display**: Real-time status of machines, axes, production lines, and parameter groups.
- **Color-Coded Indicators**: Visual alerts for critical, warning, and normal states.

### Real-Time Data Visualization
- **Dynamic Graphs**: Real-time graphs for both static and dynamic parameters.
- **Custom Queries**: Users can set specific time ranges and parameters for detailed analysis.

### Alarm Monitoring
- **Detailed Alarm Table**: List of alarms for selected machines over a chosen time period.
- **Parito and Pie Charts**: Visualization of alarm counts and timespans.

### Spare Part Management
- **Detailed Spare Part Information**: Comprehensive details for each machine's spare parts.
- **Limit Setting and Management**: Tools to add, delete, and reset spare parts, with configurable warning and critical limits.

### Special Purpose Machines (SPM) Management
- **Real-Time Parameter Monitoring**: Manage and monitor SPM machine parameters with real-time data.

### Analytics
- **Machine Analytics**: Track and analyze machine abnormalities over time.
- **Maintenance Analytics**: Monitor abnormalities managed by different operators.
- **Parameter Analytics**: Evaluate and analyze specific machine parameters.

### User Management
- **User Registration and Roles**: Add new users with defined roles and permissions.
- **Secure User Management**: Ensure secure handling of user data and restrict deletion of critical admin accounts.