#ShoppingAI
ShoppingAI is your personal fashion assistant. It helps you discover new clothing and provides personalized outfit recommendations, saving you hours of searching while helping you build the perfect outfit.
##Features
* **Smart Clothing Search:** Easily find specific clothing items using natural language (e.g., "vintage Y2K black lace crop top" or "khaki faux leather jacket").
* **AI-Powered Outfit Recommendations:** Powered by Google Gemini, the app analyzes your preferences and suggests complete, stylish outfits.
* **Personalized Experience:** Keeps track of your style preferences to offer better, more accurate recommendations over time.
* **Modern & Intuitive UI:** A seamless and responsive user interface built for fashion enthusiasts.
  
## Tech Stack

**Frontend**
* React.js
* Vite
* Vanilla CSS

**Backend**
* Java 
* Spring Boot
* Google Gemini API (AI Stylist)
* SerpApi (Google Shopping API)
## Getting Started

Follow these steps to set up the project locally on your machine.

#### Prerequisites
* **Node.js** (for running the frontend)
* **Java 17+ & Maven** (for running the backend)
* **API Keys** (Google Gemini API & SerpApi)

###### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Seher-Byte/ShoppingAI.git](https://github.com/Seher-Byte/ShoppingAI.git)
   cd ShoppingAI
2.Backend Setup:
**Navigate to the backend folder:**
``bash
  cd backend

  Open src/main/resources/application.properties and provide your valid API keys: 
  Properties
  server.port=8080
  gemini.api.key=YOUR_GEMINI_API_KEY
  serpapi.api.key=YOUR_SERPAPI_API_KEY
Run the Spring Boot server:

Bash
./mvnw spring-boot:run

3.Frontend Setup:
Open a new terminal session, navigate to the frontend folder:

Bash
cd frontend
Install dependencies and launch the Vite development server:

Bash
npm install
npm run dev
The application web client will open at http://localhost:5173.

######## Project Structure
*Plaintext
ShoppingAI/
├── backend/                # Java Spring Boot API
│   ├── src/main/java/...   # Controllers & Service layers
│   └── pom.xml             # Maven dependencies
├── frontend/               # React Vite UI Client
│   ├── src/App.jsx         # Premium UI & State management
│   └── package.json        # NPM dependencies
└── README.md
######## Developer
*Melisa Nur Aydın Software Engineering Student at Burdur Mehmet Akif Ersoy University
*Seher Tan Student at Burdur Mehmet Akif Ersoy University
*GitHub: @meliswydn

*LinkedIn: [https://www.linkedin.com/in/melisa-aydin-633690269/],[https://www.linkedin.com/in/seher-tan-1387782a3/]
