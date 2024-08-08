# ReportCraft

ReportCraft is a comprehensive web application developed to track equipment downtime, manage maintenance records, and generate efficiency reports. It supports multi-level user roles with different access levels, including engineers, department heads, supervisors, and the CEO.

## Features

- **Multi-level User Roles**:
  - **Engineer**:
    - Login and update profile.
    - Select department-specific equipment from a dropdown list.
    - Add downtime for equipment.
  - **Department Head**:
    - View and manage entries made by engineers.
  - **Supervisor**:
    - Manage data across all supervised departments.
    - Enter breakdown reasons and maintenance details.
    - Split maintenance time across different departments.
  - **CEO**:
    - View dynamic charts and reports.

- **Data Management**:
  - Engineers see equipment lists specific to their department.
  - Supervisors handle data entry, maintenance records, and efficiency tracking.
  - Annual, semi-annual, and quarterly efficiency reports.

- **Dynamic Charts and Reports**:
  - Highcharts for visualizing department and equipment data.
  - Export reports in PDF, Excel, and XML formats.

## Technologies

- **Frontend**: JavaScript, Bootstrap, Ajax
- **Backend**: ASP.NET, C#
- **Database**: MySQL
- **Charts**: Highcharts

## Setup

### Prerequisites

- Visual Studio or any C# IDE
- MySQL Server
- .NET Framework

### Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/ReportCraft.git
   cd ReportCraft
