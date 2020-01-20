# ApiCaller
Call all api methods (Post,Put,Patch,Get)
 
 
 ```
  var data = new car()
  {
      name = "BMW 1200"
  };

  ApiCaller.Call.Post<Result, car>("api.google.com", data);
```
