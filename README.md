# System_Design

# 🧠 Understanding System Design, LLD, and DSA

## 📌 What is System Design?

**System Design** is the process of defining the architecture, components, modules, interfaces, and data flow for a system to satisfy specific requirements.

### ✅ System Design includes:
- **High-Level Design (HLD)**:  
  - Focuses on the **overall architecture** of the system.  
  - Defines modules, services, databases, APIs, and communication flow.  
  - Example: User Service, Ride Service, Payment Gateway in a ride-sharing app.

- **Low-Level Design (LLD)**:  
  - Focuses on the **detailed design** of individual components.  
  - Defines classes, methods, attributes, interactions, and business logic.  
  - Example: What methods does the `User` class have? How does the `Ride` object store details?

---

## 🔍 What exactly is Low-Level Design (LLD)?

**LLD (Low-Level Design)** is a technical blueprint that describes the **internal structure of individual components or modules** in your application.

### 📚 LLD involves:
- Class diagrams
- Sequence diagrams
- Object interactions
- Method-level design
- API request/response format

> Think of LLD as how you translate HLD into actual **code structure**.

---

## ⚔️ How does LLD differ from Data Structures & Algorithms (DSA)?

| Feature               | **LLD**                                   | **DSA**                                           |
|------------------------|--------------------------------------------|---------------------------------------------------|
| Purpose                | Design of classes and logic                | Efficient data manipulation and problem solving   |
| Scope                  | Application modules                        | Data handling and computation                     |
| Focus                  | Code structure and class relationships     | Optimized logic, performance                      |
| Tools Used             | UML diagrams, interfaces, design patterns  | Arrays, Trees, Graphs, Sorting, Searching         |
| Example                | `User` class with `bookRide()` method      | Dijkstra’s Algorithm for shortest path            |

> **DSA** is a toolbox. **LLD** is how you assemble that toolbox to build something meaningful.

---

## 🔁 Relationship & Differences between HLD, LLD, and DSA

| Category        | **DSA**                           | **LLD**                                      | **HLD**                                     |
| --------------- | --------------------------------- | -------------------------------------------- | ------------------------------------------- |
| **What it is**  | Programming tools & techniques    | Detailed component/module design             | High-level architecture and system overview |
| **Used for**    | Solving individual logic problems | Planning internal logic of software features | Structuring systems into modules/components |
| **Level**       | Code/Logic level                  | Module/Class level                           | System/Application level                    |
| **Focus**       | Optimal logic and data handling   | Class design, interfaces, flows              | Services, communication between components  |
| **Who uses it** | Competitive coders, developers    | Developers                                   | Architects, senior developers               |
| **Example**     | Binary search on sorted list      | Designing `User` and `Ride` class for Uber   | Designing UserService, PaymentService, etc. |

---


> **DSA is the brain of an Application, LLD is the skeleton.**


![System Design Diagram](22b85b53-27b5-4a50-91b4-906e0673dd94.png)

---
