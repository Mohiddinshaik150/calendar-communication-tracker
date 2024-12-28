#Calendar communication tracker

This project is a React-based Calendar Application designed to efficiently track communications with companies. It helps maintain strong professional relationships by enabling timely follow-ups, managing interaction records, and scheduling communications based on predefined parameters.

## Objective

To develop a centralized platform for:
- Logging past interactions.
- Planning future communications.
- Managing communication frequency with predefined schedules.

This application includes:
- **Admin Module**: Configure companies and communication parameters.
- **User Module**: Visualize, manage, and perform communication tasks.
- **(Optional) Reporting and Analytics Module**: Actionable insights and metrics.

## Features

### Admin Module
#### Company Management
- Add, edit, and delete companies.
- Store details:
  - Name, location, LinkedIn profile, email(s), phone number(s), and comments.
  - Communication periodicity (e.g., every 2 weeks).

#### Communication Method Management
- Define available communication methods with:
  - Name (e.g., "LinkedIn Post").
  - Description (e.g., "Visit to company premises").
  - Sequence (order of communication steps).
  - Mandatory flag (if the method is required).
- Default sequence:
  1. LinkedIn Post
  2. LinkedIn Message
  3. Email
  4. Phone Call
  5. Other

### User Module
#### Dashboard
- Displays:
  - Company name.
  - Last five communications (type and date).
  - Next scheduled communication (type and date).
- Color-coded highlights:
  - **Red**: Overdue communication.
  - **Yellow**: Communication due today.

#### Interactive Features
- Tooltip on hover over completed communications to display notes.
- Log communication actions with:
  - Type, date, and notes.

#### Notifications
- Overdue and today’s communications displayed in grids.
- Notification badge for the total count.

#### Calendar View
- View past communications by date and method.
- Manage upcoming communications.

### Reporting and Analytics Module (Optional)
- Communication Frequency Report:
  - Visual representation of communication methods (e.g., bar chart).
- Engagement Effectiveness Dashboard:
  - Metrics on response rates by method.
- Overdue Communication Trends:
  - Trendline of overdue communications over time.
- Downloadable Reports (PDF/CSV).
- Real-Time Activity Log.

## Development Instructions

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/calender-communication-tracker.git
   
_Development Instructions_
To run this project locally, follow these steps:

_Clone the repository to your local machine._
Navigate to the project directory.
Install dependencies using npm install.
Run the development server using npm start.
Open your browser and go to http://localhost:3000 to view the application.

## Contributing

Contributions to this project are welcome. If you would like to contribute, please fork the repository, make your changes, and submit a pull request.
