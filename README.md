# Connected - Campus Events Platform

Connected is a modern web application designed specifically for college students to discover, create, and manage campus events. It helps students stay informed about what's happening on their campus and connect with others who share similar interests.

## Features

- **Event Discovery**: Browse through various campus events filtered by type (social, sports, academic, etc.)
- **Friend Integration**: See how many of your friends are attending each event
- **Event Creation**: Create and manage your own campus events
- **User Profiles**: Personal profiles to showcase your interests and event history
- **Responsive Design**: Fully responsive interface that works on all devices
- **Real-time Updates**: Stay updated with the latest campus happenings

## Event Categories

- Social Events
- Sports Activities
- Academic Events
- Other Campus Activities

## Technology Stack

- **Backend**: Python/Flask
- **Database**: SQLite with SQLAlchemy ORM
- **Frontend**: HTML5, CSS3, Bootstrap 5
- **Authentication**: Flask-Login with password hashing
- **Forms**: Flask-WTF with validation

## Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/jeffreyzhou-harvard/connectedapp.git
cd connectedapp
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
Create a `.env` file with the following:
```
SECRET_KEY=your-secret-key-here
DATABASE_URL=sqlite:///app.db
FLASK_ENV=development
FLASK_DEBUG=1
```

5. Initialize the database:
```bash
flask db init
flask db migrate
flask db upgrade
```

6. Run the application:
```bash
flask run
```

7. Visit `http://localhost:5000` in your browser

## Usage

1. **Registration**: Create an account with your college email
2. **Browse Events**: View all campus events or filter by type and friend count
3. **Create Events**: Post your own events for others to discover
4. **Connect**: See which of your friends are attending events
5. **Manage**: Edit or delete your own events

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- CS50 Web Programming with Python and JavaScript
- Flask Documentation
- Bootstrap Team 