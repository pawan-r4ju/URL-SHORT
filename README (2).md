
# QUIZY server





## API Reference

#### Get all items
it is a custom made simple api json
```http
  https://server-zumh.onrender.com
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `REACT_APP_API_BASE_URL` | `string` | **Required**. Your API key |

ALSO YOU CAN RUN LOCALLY BY USING THESE COMMANDS

```http
npm install json-server --save-dev

npx json-server --watch db.json

```




## db.json structure
it is deployed on the vercel and server is deployed on the render

To deploy this project run

```bash
  {
    "questions": [
      {
        "id": 1,
        "question": "What is the capital of France?",
        "options": ["Paris", "London", "Berlin", "Madrid"],
        "answer": "Paris"
      },
      {
        "id": 2,
        "question": "What is 2 + 2?",
        "options": ["3", "4", "5", "6"],
        "answer": "4"
      }
    ]
  }
  
```


