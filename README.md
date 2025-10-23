# Supply Chain Tracking System
A Python-based supply chain and logistics tracking system implemented using Object-Oriented Programming (OOP) principles.
                                                                                                                                                                                       🧭 Overview

This project demonstrates how object-oriented programming can be applied to design and manage a supply chain tracking system.
It simulates the process of creating shipments, tracking them across various stages, generating reports, and handling exceptions — all organized into modular Python files.

The program can be extended for real-world logistics applications such as route tracking, shipment monitoring, and data reporting.


🗂️ Project Structure

supply_chain_tracking/
│
├── main.py          # Entry point (menu-driven program)
├── shipment.py      # Shipment class
├── tracker.py       # Tracker class to manage multiple shipments
├── report.py        # Reporting and shipment history
├── exceptions.py    # Custom exceptions
├── utils.py         # Helper utilities
│
├── data/
│   └── sample_data.json   # Optional dataset for demo
│
└── README.md        # Project details + instructions


---

⚙️ Features

✅ Object-oriented design (encapsulation, abstraction, inheritance, polymorphism)
✅ Add and manage multiple shipments
✅ Track shipment status and history
✅ Generate and export reports
✅ Handle exceptions and invalid operations safely
✅ Modular and easy-to-extend Python codebase


---

🧩 OOP Concepts Used

Concept	How It’s Used

Encapsulation	Shipment and Tracker classes hide internal data using private attributes and methods.
Abstraction	Interfaces like Tracker and Report abstract complex logic behind simple methods.
Inheritance	Can be extended for specialized shipment types (e.g., ExpressShipment, InternationalShipment).
Polymorphism	Common interface for updating and displaying shipment info, even if subclasses differ.

🚀 How to Run

1. Clone the repository

git clone https://github.com/LIKU-JENA/supply_chain_tracking.git
cd supply_chain_tracking


2. Run the main program

python main.py


3. Follow the menu prompts to add, update, track, and generate shipment reports.

📊 Example Flow

Step 1: Add new shipment
Step 2: Update shipment status (e.g., “In Transit”, “Delivered”)
Step 3: View all active shipments
Step 4: Generate tracking reports

Example (pseudo output):

Shipment ID: SHP102
Origin: Mumbai
Destination: Delhi
Status: In Transit
Last Updated: 2025-10-22 14:30

📁 Sample Data

A demo file (data/sample_data.json) is included to simulate preloaded shipments.
Example snippet:

[
  {
    "shipment_id": "SHP001",
    "origin": "Chennai",
    "destination": "Hyderabad",
    "status": "Delivered"
  }

🧑‍💻 Tech Stack

Language: Python 3.x

Paradigm: Object-Oriented Programming (OOP)

Libraries:Spider



