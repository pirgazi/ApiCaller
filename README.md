# ApiCaller
Call all api methods (Post,Put,Patch,Get)
 
 ** For Example : **
 ```
  var data = new car()
  {
      api-key = "121d@F$14",
      username = "Pirgazi"
  };

  ResponseModel result = ApiCaller.Call.Post<RequsetModel, ResponseModel>("api.google.com", data);
```
