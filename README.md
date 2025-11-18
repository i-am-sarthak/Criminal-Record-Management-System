# Criminal Record Management System

A desktop application built using **Java** and **JavaFX** that provides a simple and intuitive interface to create, update, view, and delete criminal records. Designed using a modular **MVC-style architecture**, the system allows users to manage FIR details, crime information, and criminal profiles efficiently.

---

## Features

### 🔹 Add New Records
- Enter FIR date, criminal ID, crime description, and address  
- Field validation prevents empty or invalid submissions  
- Instant UI updates using JavaFX observable properties  

### 🔹 Edit Existing Records
- Select a record from the list and update any field  
- Changes automatically reflected in the table view  

### 🔹 Delete Records
- Remove unwanted records instantly  
- Safety prompts to avoid accidental deletions  

### 🔹 View Records in a Table
- Interactive JavaFX TableView listing all registered criminal records  
- Real-time updates when records change  

### 🔹 Clean MVC Architecture
- Separate **Model**, **Views**, and **Controllers**  
- Easier to scale, debug, and maintain  

---

## Tech Stack

| Category      | Technologies |
|---------------|--------------|
| Language      | **Java** |
| UI Framework  | **JavaFX** |
| Architecture  | MVC-style (Controllers, Views, Model) |
| Data Handling | JavaFX `ObservableList`, property bindings |
| Build Tool    | Maven |

---

## How to Run

### Prerequisites
- Java 11 or above  
- Maven  
- JavaFX SDK (if your IDE does not bundle it)

### Steps

```bash
# Clone the repository
git clone https://github.com/<your-username>/Criminal-Record-Management-System.git

# Navigate into project folder
cd Criminal-Record-Management-System

# Run with Maven
mvn clean javafx:run


