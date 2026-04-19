SENTINALS: AI-Driven Predictive Maintenance System for Mining Equipment
 
Overview
As industries move toward Industry 4.0 and Industrial IoT (IIoT), Small and Medium Enterprises (SMEs) are still stuck with reactive and schedule-based maintenance.
This results in:
•	Unexpected machine breakdowns
•	Production losses
•	Safety hazards
•	High operational costs

Sentinels is a modular, AI-powered predictive maintenance system designed to bridge this gap and bring smart maintenance to SMEs.

What This Project Does
Sentinels continuously monitors industrial machinery, detects anomalies, predicts failures, and provides actionable insights through an intelligent dashboard.
Core Features
1. Real-Time IoT Data Acquisition
Sensors capture:
•	Temperature
•	Vibration
•	Current
•	Pressure
Data is collected via ESP32 microcontrollers and transmitted to the edge system.
2. Edge Processing with Raspberry Pi
Data is routed to a Raspberry Pi (edge server)
 3. AI-Based Anomaly Detection
Uses:
•	Isolation Forest (for anomaly detection)
•	Random Forest (for baseline modeling)
System:
•	Learns normal machine behavior
•	Detects anomalous patterns in real-time
•	Triggers alerts instantly

4. Digital Twin System
•	Provides visual representation of machine faults
•	Highlights affected components based on:
	Parameter spikes
	Pattern combinations
	Enables quick fault localization
5. Master Health Index & RUL Prediction
	Individual Health Index for each parameter
	Aggregated into a Master Health Index
	Remaining Useful Life (RUL) is calculated based on degradation trends


6. Monetary Loss Analysis
Tracks abnormal current spikes
Converts energy waste into:
	Daily losses
	Annual losses
	Helps industries understand financial impact of inefficiencies

7. Worker Health & Safety Monitoring
Monitors:
	Ambient temperature
	Harmful gas concentration
 Triggers:
	Visual alerts
	Audio alarms
	Ensures fail-safe human protection

8. Interactive Dashboard
Includes:
	Live sensor readings
	Remaining Useful Life
	ESG tracking & loss analysis
	Digital twin visualization
	Alerts & anomaly logs
	System Architecture

Workflow:
Sensors → ESP32 → Raspberry Pi → AI Models → Dashboard
	Sensors capture real-time machine data
	ESP32 transmits data
	Raspberry Pi processes and analyzes
	ML models detect anomalies
	Dashboard displays insights & alerts

 Tech Stack
Hardware
1.	ESP32 Microcontroller
2.	Raspberry Pi
3.	Industrial Sensors
Software
1.	Python
2.	MQTT Protocol
3.	Machine Learning Models
4.	Web Dashboard
5.	ML Algorithms
6.	Isolation Forest
7.	Random Forest

Unique Selling Points
1.	100% Air-Gapped Cybersecurity (no cloud dependency)
2.	Real-time Edge Processing
3.	AI-powered diagnostics via Digital Twin
4.	Integrated worker safety monitoring
5.	SMS alerts for hazardous conditions
6.	Direct ESG & financial impact tracking
7.	Low-cost  deployment

Impact & Benefits
1.	Eliminates catastrophic downtime
2.	Improves machine lifespan
3.	Reduces maintenance costs
4.	Enhances worker safety
5.	Enables ESG compliance
6.	Provides high ROI with minimal CapEx

 Future Scope
1.	Expansion Beyond Mining
2.	Oil & Gas (pipeline failure detection)
3.	Manufacturing (equipment fouling)
4.	Power Generation (turbine health monitoring)
5.	Construction (heavy machinery maintenance)


Market Opportunity
 $50B annual loss due to downtime
 $23.9B predictive maintenance market


 Business Model
1.	Zero CapEx Deployment (~₹6,700/node hardware at cost)
2.	Performance-Based SLA (15% commission on savings)
3.	Enterprise API Licensing (₹49,999/year)
4.	Current Status
5.	Working prototype developed
6.	Real-time monitoring functional
7.	Scaling to multi-industry deployment

