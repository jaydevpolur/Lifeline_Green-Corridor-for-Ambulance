# **Lifeline: Green Corridor for Ambulance and AI Disease Prediction System**

#### **Overview**
LifeLine is a comprehensive web application built using Streamlit, designed to streamline emergency medical services and assist in disease prediction. The system integrates features for real-time ambulance allocation, optimized hospital routing, and symptom-based AI disease prediction, ensuring faster and more efficient healthcare responses.

---

#### **Key Features**
- **Real-Time Ambulance Allocation**  
  Dynamic mapping and dispatching for quickest response.

- **Optimized Hospital Routing**  
  Intelligent algorithms for shortest and safest routes.

- **AI Disease Prediction**  
  Input symptoms, get probable diagnoses instantly.

- **Intuitive Dashboard**  
  Simple UI for emergency operators and medical staff.

---

#### **Technologies Used**
- **Python**: Core logic implementation.
- **Streamlit**: Web application framework for interactive user interfaces.
- **Folium**: For map rendering and visualization.
- **Geopy**: Geocoding and distance calculations.
- **OpenRouteService API**: For route optimization and directions.
- **Overpass API**: For real-time hospital and traffic signal data.

---

#### **How It Works**
1. **Emergency Response Workflow**:
   - Input the patient's location and desired hospital specialization.
   - The system geocodes the location, finds the nearest hospital or ambulance, and calculates the fastest route.
   - Simulated traffic signals are displayed along the route to visualize travel delays.

2. **Disease Prediction Workflow**:
   - Select up to 4 symptoms from a predefined list.
   - The system matches the input symptoms with known diseases in the dataset.
   - Displays the predicted disease and provides its description.

---

#### **Installation and Usage**
1. Clone the repository:
   ```bash
   git clone https://github.com/jaydevpolur/Lifeline_Green-Corridor-for-Ambulance.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Lifeline_Green-Corridor-for-Ambulance
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   streamlit run app.py
   ```
5. Access the application at `http://localhost:8501`.

---

⚡ Usage
- Launch the app using Streamlit.
- Register or log in as a dispatcher or medical staff.
- Access ambulance tracking, routing, and disease prediction modules.
- Respond to emergencies with optimized workflow!

#### **Future Enhancements**
- Integrate real-time traffic data for more accurate travel time estimation.
- Expand the disease prediction system using machine learning models.
- Implement GPS-based live ambulance tracking.
- Enhance scalability to include multiple cities.
