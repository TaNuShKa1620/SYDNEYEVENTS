# SYDNEYEVENTS
An automated event discovery platform for Sydney that aggregates events from multiple sources and presents them in a beautiful dark-themed interface.

## Features

- Automated event scraping from popular Sydney event websites
- Beautiful dark-themed responsive user interface
- Email capture system before redirecting to ticket pages
- Detailed event pages with comprehensive information
- Category filtering and search capabilities
- Automatic event updates with scheduled scraping

## Tech Stack

### Frontend
- React with TypeScript
- Tailwind CSS for styling
- Framer Motion for animations
- React Query for data fetching
- React Router for navigation

### Backend
- Python Flask API
- BeautifulSoup for web scraping
- Scheduled scraping with threading

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- Python 3.8+ (for the scraper API)

### Installation

1. Clone the repository
```
git clone https://github.com/yourusername/sydney-events-platform.git
cd sydney-events-platform
```

2. Install frontend dependencies
```
npm install
```

3. Install backend dependencies
```
cd api
pip install -r requirements.txt
cd ..
```

### Running the application

1. Start the backend API (in one terminal)
```
npm run start-api
```

2. Start the frontend development server (in another terminal)
```
npm run dev
```

3. Open your browser and navigate to the URL shown in your terminal

## Project Structure

```
sydney-events-platform/
├── api/                 # Python backend
│   ├── app.py           # Flask API and scraper
│   └── requirements.txt # Python dependencies
├── public/              # Static assets
├── src/                 # React frontend
│   ├── components/      # Reusable components
│   ├── pages/           # Page components
│   ├── services/        # API services
│   ├── types/           # TypeScript types
│   ├── App.tsx          # Main app component
│   └── main.tsx         # Entry point
└── README.md            # This file
```
# images of the frontend 
![Screenshot 2025-05-29 135620](https://github.com/user-attachments/assets/c149f42e-2be1-48a2-93aa-02b7a518eed1)
![Screenshot 2025-05-29 135706](https://github.com/user-attachments/assets/e9717ff9-4fe9-406e-8ad0-ef748698baa7)
![Screenshot 2025-05-29 135752](https://github.com/user-attachments/assets/eacacff6-362b-4a30-a1ad-742c579a9559)
![Screenshot 2025-05-29 135804](https://github.com/user-attachments/assets/afdcb756-6ae0-4ee1-9ef2-92e1d2b6c669)
![image](https://github.com/user-attachments/assets/c0f8a18f-2fee-4cf9-8927-09d43985c367)




## Customization

- Modify the scraper sources in `api/app.py` to target different event websites
- Adjust the scraping interval by changing the `scrape_interval` variable
- Customize the UI theme in `tailwind.config.js`

## License

This project is licensed under the MIT License.
