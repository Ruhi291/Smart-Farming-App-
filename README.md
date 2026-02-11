#  Smart Farming Assistant for Canada

AI-powered agricultural guidance system helping Canadian farmers make informed decisions using Google Gemini 2.0 Flash.

##  Overview

The Smart Farming Assistant is a web-based application designed specifically for Canadian farmers to receive personalized, AI-generated recommendations for crop management. The app considers regional climate patterns, seasonal variations, and crop-specific requirements to provide actionable farming advice.

##  Purpose

Canadian farmers face unique challenges including:
- Short growing seasons
- Unpredictable weather patterns
- Frost risks
- Regional climate variations across provinces

This app addresses these challenges by providing instant, AI-powered guidance tailored to each farmer's specific situation.

##  Features

### 1. **Farm Profile Input**
- Province selection (all 10 Canadian provinces)
- Season tracking (Spring, Summer, Fall, Winter)
- Crop stage monitoring (Pre-Planting, Planting, Growing, Harvesting, Post-Harvest)
- Personalized farmer profiles

### 2. **Crop Selection**
Four major Canadian crops supported:
-  Wheat
-  Canola
-  Barley
-  Oats

### 3. **AI-Powered Recommendations**
The app generates four categories of advice:

**🌡️ Weather-Based Guidance**
- Frost warnings
- Precipitation tracking
- Temperature monitoring
- Seasonal weather patterns

** Pest & Disease Management**
- Crop-specific pest identification
- Disease prevention strategies
- Integrated pest management (IPM)
- Scouting recommendations

*Soil & F ertilizer Guidance**
- Nutrient recommendations
- pH balance advice
- Fertilizer application timing
- Soil health maintenance

** Sustainable Farming Practices**
- Crop rotation strategies
- Water conservation techniques
- Organic farming methods
- Environmental protection

### 4. **Goal Tracking System**
Track your farming journey with achievements:
- Complete assessments
- Explore different crops
- Experience all seasons
- Build farming expertise

### 5. **Additional Features**
-  Weather Forecast - 7-day outlook
-  Market Prices - Current commodity prices
-  Community Tips - Shared farmer wisdom
-  Assessment History - Track past recommendations

## 🛠️ Technology Stack

- **Frontend Framework:** Streamlit
- **AI Model:** Google Gemini 2.0 Flash
- **Language:** Python
- **API:** Google Generative AI

## 🚀 How It Works

1. **User Input**: Farmer enters their profile information (name, province, season, crop stage)

2. **Crop Selection**: Choose from wheat, canola, barley, or oats

3. **AI Processing**: Google Gemini 2.0 Flash analyzes the input and generates contextual recommendations based on:
   - Regional climate data
   - Seasonal factors
   - Crop-specific requirements
   - Best farming practices

4. **Output Generation**: The app displays four categories of detailed recommendations tailored to the farmer's specific situation

5. **History Tracking**: All assessments are saved for future reference

##  Installation & Setup

### Prerequisites
- Python 3.8+
- Google Gemini API Key

### Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/smart-farming-assistant.git
cd smart-farming-assistant
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Set up API key**

Create `.streamlit/secrets.toml`:
```toml
GEMINI_API_KEY = "your-gemini-api-key-here"
```

4. **Run the application**
```bash
streamlit run app.py
```

5. **Access the app**
Open your browser to `http://localhost:8501`

##  Requirements
```txt
streamlit
google-generativeai
```

##  Live Demo

🔗 **[View Live App]** - [Your Streamlit Cloud URL]

## 📸 Screenshots

[Add 3-5 screenshots showing:
- Dashboard
- Farm profile input
- Crop selection
- AI recommendations output
- Goals page]

##  User Interface

The app features:
- Clean, intuitive design
- Dark, readable headings
- Color-coded information cards
- Responsive layout
- Easy navigation with sidebar menu

##  Testing

The application has been tested with:
- All 4 crop types (Wheat, Canola, Barley, Oats)
- All 4 seasons (Spring, Summer, Fall, Winter)
- Multiple provinces across Canada
- All 5 crop stages
- Various weather conditions

##  Security

- API keys stored securely in `secrets.toml`
- `.streamlit/` folder added to `.gitignore`
- No sensitive data exposed in repository

##  Use Cases

### For Small-Scale Farmers
- Quick access to expert advice without hiring consultants
- Cost-effective decision-making support
- Learn best practices for their region

### For Agricultural Students
- Educational tool for learning crop management
- Understanding regional farming differences
- Exploring sustainable practices

### For Agricultural Extension Workers
- Digital tool to support farmer training
- Consistent information delivery
- Scalable advisory service

## 📈 Future Enhancements

Potential improvements for future versions:
- Integration with real-time weather APIs
- Soil test result analysis
- Crop yield prediction
- Multi-language support (French for Quebec)
- Mobile app version
- Image upload for pest identification
- Market price predictions
- Farm expense tracking

##  Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## 📄 License

MIT License - feel free to use this project for educational purposes.

##  Developer

**[Your Name]**
- Student ID: [Your ID]
- Institution: [Your School]
- Email: [Your Email]

##  Acknowledgments

- Google Gemini AI for providing the AI model
- Streamlit for the web framework
- Canadian agricultural extension services for farming knowledge
- Agriculture and Agri-Food Canada for reference materials

##  Support

For questions or support, please:
- Open an issue on GitHub
- Contact: [your-email@example.com]

---

##  Conclusion

The Smart Farming Assistant successfully demonstrates how AI technology can be applied to solve real-world agricultural challenges in Canada. By providing personalized, instant recommendations, the app empowers farmers with knowledge traditionally requiring expensive consultants or extensive research.

Key achievements:
-  Functional AI-powered recommendation system
-  User-friendly interface for farmers of all technical levels
-  Comprehensive coverage of major Canadian crops
-  Region-specific and season-aware advice
-  Integration of multiple farming aspects (weather, pests, soil, sustainability)

This project bridges the gap between advanced AI technology and practical farming needs, making agricultural expertise more accessible to Canadian farmers across all provinces and experience levels.

**Future Impact**: As AI technology advances, tools like this can help address food security challenges, promote sustainable farming practices, and support the next generation of Canadian agriculture.

---

** Star this repository if you find it helpful!**

**🌾 Happy Farming! 🇨🇦**
