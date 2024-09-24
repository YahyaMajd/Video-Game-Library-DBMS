# Video Game Library Database

## Overview and Context
This project involves designing and implementing a relational database to manage a video game library. The database contains several tables, including Player, Game Series, and Tournament, and supports complex data modeling through relationships. A PHP web interface connects to the Oracle database, allowing users to interact with the data by adding, updating, or removing entries in real-time. Note : This project requires an OracleSQL license to run.

## Features

- **Relational Database Design:** The database is structured with tables such as `Player`, `Game Series`, and `Tournament`. It models complex relationships, including:
  - **One-to-One Relationships:** For example, each professional player can have one dedicated coach, while recreational players do not.
  - **One-to-Many Relationships:** Linking companies to the `Game Series` table, where a single company can develop multiple game series.

- **Player Categorization:** Distinguishes between recreational and professional players. Recreational players are linked to casual tournaments, while professional players participate in major competitions.

- **Web Interface:** 
  - Developed a PHP-based web interface connected to the Oracle database.
  - Users can interact with the database by adding new entries, modifying existing data, or removing records.
  - The interface invokes OracleSQL calls dynamically based on user interactions.

- **Dynamic Querying:** 
  - Implemented features that allow users to perform customized searches and data retrieval.
  - Supports real-time updates to the database based on user actions, ensuring that the information displayed is always up-to-date.

## Technologies Used

- **Oracle Database:** Relational database for managing complex data relationships.
- **PHP:** Server-side scripting language for building the interactive web interface.
- **OracleSQL:** Used for creating, querying, and managing the database structure and data.

## Getting Started

### Prerequisites
- Oracle Database installed and configured.
- PHP installed on the web server.
- Web browser for accessing the PHP interface.

