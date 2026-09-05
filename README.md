# Stage 0 - Backend Task (HNG)

## Task Description
This project is a simple API endpoint that returns:
- My **name**
- My **email**
- My **programming language/framework**
- The **current timestamp** (in ISO 8601 format)
- A **random cat fact** fetched dynamically from [Cat Fact API](https://catfact.ninja/)

### Example JSON Response
```json
{
  "status": "success",
  "user": {
    "email": "omotayoisrael24@gmail.com",
    "name": "Omotayo Israel",
    "stack": "Python/Django"
  },
  "timestamp": "2025-10-19T13:45:12Z",
  "fact": "Cats sleep 70% of their lives."
}
