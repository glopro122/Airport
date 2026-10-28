# Airport & Flight Operations Management System

![Java](https://img.shields.io/badge/Java-17%2B-orange?logo=openjdk)
![GUI](https://img.shields.io/badge/GUI-Java_Swing-blue)
![Paradigm](https://img.shields.io/badge/Paradigm-Object--Oriented_Design-success)

An Object-Oriented desktop software application developed in Java with a Swing graphical interface. The system simulates airline operations including flight scheduling, passenger seat allocations, route management, and fleet coordination.

---

## 📌 Key Architectural Highlights

* **Domain-Driven OOP Design:** Built using strict Object-Oriented principles (abstraction, encapsulation, inheritance).
  * `Flight.java`: Manages flight numbers, departure/arrival schedules, origin/destination mappings, and status.
  * `Plane.java`: Handles aircraft capacity, model properties, and seating configurations.
  * `Passenger.java`: Represents traveler profiles and boarding assignments.
  * `Location.java`: Models airports, hubs, and terminal destinations.
* **Modular Event-Driven UI:**
  * Implemented using **Java Swing** (`AirportFrame.java`).
  * Features custom styled containers (`PanelRound.java`) for smooth, card-based modern UI aesthetics.
  * Decouples user interactions and visual events from backend domain state.

---

## 📂 Project Structure

```
Airport/
├── src/
│   └── airport/
│       ├── AirportFrame.java      # Main GUI window & event listeners
│       ├── AirportFrame.form      # Swing GUI layout designer
│       ├── Flight.java            # Flight domain model
│       ├── Plane.java             # Aircraft fleet model
│       ├── Passenger.java         # Passenger entity & ticket logic
│       ├── Location.java          # Airport destination model
│       └── PanelRound.java        # Custom modern rounded JPanel component
├── build.xml                      # Apache Ant build definition
└── README.md
```

---

## 🚀 How to Build and Run

### Prerequisites
* Java Development Kit (JDK 17 or higher)
* Apache Ant (or any standard Java IDE like IntelliJ IDEA, NetBeans, or VS Code)

### Running via Apache Ant:
```bash
git clone https://github.com/glopro122/Airport.git
cd Airport
ant run
```

### Running via IDE:
1. Open the project directory in your IDE of choice.
2. Ensure the JDK is configured.
3. Run `src/airport/AirportFrame.java` as the main entry point.

---

## 👨‍💻 Author
Developed by **Manuel González** (Systems and Computer Engineering, Universidad del Norte).
