# 🚣️ PathX

An AI/ML-powered route planner and inventory dashboard for logistics optimization.

## 🔧 Features
- 📍 Route planning using OpenRouteService
- 🌱 CO₂ emission calculation based on vehicle type
- �� Editable inventory dashboard with stock indicators
- 🌍 Interactive map via Folium
- 💡 Built with Streamlit and Python

## 🚀 Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/your-majisty174/pathx4.git
cd pathx4
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv
# On Unix or MacOS
source venv/bin/activate
# On Windows
venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the app
```bash
streamlit run src/dashboard/main.py
```

The app will open in your browser at `http://localhost:8501`

## 📁 Project Structure
```
pathx4/
├── data/                      # Raw and processed data files
├── notebooks/                 # Jupyter notebooks for analysis and experimentation
├── src/
│   ├── api/                   # Route API client (OpenRouteService)
│   ├── dashboard/             # Streamlit frontend (main.py + inventory UI)
│   ├── models/                # ML and optimization models (planned)
│   └── utils/                 # Utility functions and helpers
├── tests/                     # Test files
├── requirements.txt           # Python dependencies
├── .gitignore
├── README.md                  # You're here
```

## 🌐 External Services Used
- [OpenRouteService](https://openrouteservice.org/) — Routing API (free tier available)
- [Streamlit](https://streamlit.io/) — App framework
- [Folium](https://python-visualization.github.io/folium/) — Map rendering

## 🧪 Current Capabilities
- Fetch optimized driving routes between any origin and destination
- Calculate CO₂ output for each trip based on vehicle class
- Interact with an editable, real-time inventory dashboard
- Visualize route maps with waypoints and paths on an embedded map

## 🧪 Development

### Run tests
```bash
pytest tests/
```

### Format code
```bash
black src/
```

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 👤 Author
[@your-majisty174](https://github.com/your-majisty174)

---
> ⚙️ Future roadmap: ML predictions, smart restocking alerts, carbon reporting, and fleet optimization.

© 2024 PathX - Logistics Optimization Platform
