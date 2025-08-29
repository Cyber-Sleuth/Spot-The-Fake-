# Spot-The-Fake-
This project, "Spot The Fake - Advanced Threat Detection Dashboard," is a comprehensive security application designed to analyze URLs and Android APK files for phishing, malware, and other cyber threats. 

---

## ⚙️ Getting Started

### Prerequisites
- Python **3.9+**
- Node.js **16+** with npm or yarn
- [VirusTotal API key](https://www.virustotal.com/gui/join-us) (free or paid)
- Git

---

### 🔹 Backend Setup (FastAPI)

```bash
# Clone the repository
git clone https://github.com/yourusername/spot-the-fake.git
cd spot-the-fake/backend

# Create & activate virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set your VirusTotal API key
export VIRUSTOTAL_API_KEY="your_api_key_here"   # On Windows: setx VIRUSTOTAL_API_KEY "your_api_key_here"

# Run FastAPI server
uvicorn app.main:app --reload --host 0.0.0.0 --port 8000

🔹 Frontend Setup (React)
cd ../frontend

# Install frontend dependencies
npm install    # or yarn install

# Start React dev server
npm start      # or yarn start
