
## Database README.md

```markdown
# Party of Artificial Intelligence (PAI) - Database

## Project Overview
The Database for the Party of Artificial Intelligence (PAI) project stores community data, survey responses, and historical records related to Calgary's societal challenges. MongoDB is used to support dynamic data retrieval for insights and predictions.

## Features
- **Community Data Storage**: Stores survey responses, crime reports, housing data, and economic indicators.
- **Historical Data Retrieval**: Enables API calls to fetch historical data for predictive modeling.
- **Secure Data Access**: Data access controlled by role-based access (RBAC) and SSL/TLS encryption.

## Technology Stack
- **MongoDB**: A NoSQL database for flexible, document-based data storage.
- **MongoDB Atlas**: For cloud-based, scalable database hosting with built-in security.

## Database Structure
- **Collections**:
  - `housing_data`: Contains housing trends, prices, and forecasts.
  - `crime_data`: Stores records of crime reports and safety patterns.
  - `community_feedback`: Stores survey responses and public sentiment data.

## Data Management
1. **Data Retrieval**: Data is fetched by the Back-End API based on requested parameters.
2. **Real-Time Updates**: Data is updated continuously to provide accurate, up-to-date insights.

## License
This project is licensed under the MIT License.

