# Travel Tracker 🗺️

A web application that allows users to track and visualize countries they've visited on an interactive world map.

## Features

- Interactive world map visualization
- Add countries you've visited
- Delete individual countries
- Reset all visited countries
- Real-time map updates
- Case-insensitive country search
- Partial name matching support
- Error handling for invalid entries
- Total countries counter

## Screenshots

### Homepage

Initial view of the application
![Home Page](/public/images/homepage.png)

### Adding a Country

Entering a country name to mark as visited
![Add Country](/public/images/add_country.png)

### Updated Map

Map showing the newly added country highlighted in green
![Added Country](/public/images/added_country.png)

## Technologies Used 🛠️

- **Frontend**:

  - HTML
  - CSS
  - JavaScript
  - EJS (Embedded JavaScript templating)

- **Backend**:
  - Node.js
  - Express.js
  - PostgreSQL
  - dotenv

## Setup and Installation 🚀

1. Clone the repository:

```bash
git clone https://github.com/yourusername/travel-tracker.git
```

2. Install dependencies:

```bash
cd travel-tracker
npm install
```

3. Set up your PostgreSQL database and create a `.env` file with your credentials:

```env
user=your_username
host=your_host
database=your_database_name
password=your_password
port=your_port
```

4. Run the application:

```bash
node index.js
```

5. Open your browser and navigate to:

```
http://localhost:3000
```

## Database Schema

The application uses two main tables:

- `countries`: Stores country names and their corresponding codes
- `visited_countries`: Tracks which countries have been marked as visited

## Usage

1. **Add a Country**:

   - Enter the country name in the input field
   - Click the "ADD" button
   - The country will be highlighted in green on the map

2. **Delete a Country**:

   - Enter the country name in the delete input field
   - Click the "DELETE" button
   - The country will return to its default color

3. **Reset All**:
   - Click the "DELETE ALL" button in the top right corner
   - All countries will return to their default color

## Contributing

Feel free to submit issues, fork the repository, and create pull requests for any improvements.
