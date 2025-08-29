# Spot-The-Fake-
This project, "Spot The Fake - Advanced Threat Detection Dashboard," is a comprehensive security application designed to analyze URLs and Android APK files for phishing, malware, and other cyber threats. 
Getting Started
Prerequisites

    Python 3.9+

    Node.js 16+ and npm or yarn

    VirusTotal API key (free or paid)

    Git

Backend Setup (FastAPI)

    Clone the repository:

bash
git clone https://github.com/yourusername/spot-the-fake.git
cd spot-the-fake/backend

    Create and activate a virtual environment:

bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

    Install backend dependencies:

bash
pip install -r requirements.txt

    Set your VirusTotal API key as an environment variable:

bash
export VIRUSTOTAL_API_KEY="your_api_key_here"    # On Windows: setx VIRUSTOTAL_API_KEY "your_api_key_here"

    Run the FastAPI server:

bash
uvicorn main:app --reload --host 0.0.0.0 --port 8000

The backend API will be accessible at http://localhost:8000
Frontend Setup (React)

    Navigate to the frontend folder:

bash
cd ../frontend

    Install frontend dependencies:

bash
npm install

or

bash
yarn install

    Start the React development server:

bash
npm start

or

bash
yarn start

Open a browser and go to http://localhost:3000 to view the dashboard.
Environment Configuration

    Make sure the React frontend fetch URLs point to your backend (http://localhost:8000 by default).

    Set your VirusTotal API key properly for backend scanning.
