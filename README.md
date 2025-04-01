## Task 1 - _Generative AI basics_

### How to run the project:
- Configure your `API_CLIENT_KEY` & `CLIENT_ENDPOINT` as VM arguments
- Run the spring boot application - `GenAiTrainingApplication`
- You can use tools like `Postman` to fire REST API calls to use the app

---
### How to provide request:
Pass input as request parameter: 
e.g.
`?input=describe the stock market briefly`


---
### Request examples:
### 1. 
- _REQUEST URL:_ `localhost:8080/api/chat?input=describe the stock market briefly`
- _RESPONSE_:  
``` 
{
    "input": "describe the stock market briefly",              
    "response": "The stock market is a marketplace where investors buy and sell shares of publicly traded companies. It helps companies raise capital and gives investors a chance to earn returns. Prices of stocks change based on supply and demand, influenced by factors like company performance, economic news, and investor sentiment. Major stock markets include the New York Stock Exchange (NYSE) and Nasdaq."
}
```


