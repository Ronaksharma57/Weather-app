# Weather-app

# html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Weather App</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="container">
      <h1>Weather App</h1>
      <form>
        <input type="text" id="city-input" placeholder="Enter City" />
        <input type="submit" value="Get Weather" />
      </form>
      <div id="weather-data">
        <div class="icon">
        </div>
        <div class="temperature"></div>
        <div class="description"></div>
        <div class="details">
        </div>
      </div>
    </div>
    <script src="index.js"></script>
  </body>
</html>
```
# css
```
body {
    margin: 0;
    font-family: "Montserrat", sans-serif;
    background-color: #f7f7f7;
  }
  
  .container {
    background-color: #fff;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
    margin: 0 auto;
    margin-top: 50px;
    text-align: center;
    max-width: 600px;
    border-radius: 5px;
    padding: 20px;
  }
  
  form {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 20px;
  }
  
  form input[type="text"] {
    padding: 10px;
    border: none;
    outline: none;
    font-size: 18px;
    width: 60%;
  }
  
  form input[type="submit"] {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    font-size: 18px;
    cursor: pointer;
    outline: none;
    transition: background-color 0.3s ease;
  }
  
  form input[type="submit"]:hover {
    background-color: #0062cc;
  }
  
  .icon img {
    width: 100px;
    height: 100px;
    background-size: contain;
    background-repeat: no-repeat;
    background-position: center center;
  }
  
  .temperature {
    font-size: 48px;
    font-weight: bold;
    margin: 20px 0;
  }
  
  .description{
      font-size: 24px;
      margin-bottom: 20px;
  }
  
  .details{
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
  }
  
  .details > div{
      padding: 20px;
      background-color: #f1f1f1;
      margin: 10px;
      flex: 1;
      border-radius: 5px;
      text-align: center;
      min-height: 45px;
  }
  
  @media (max-width: 768px){
      form {
          flex-direction: column;
      }
  
      form input[type="text"]{
          width: 100%;
          margin-bottom: 10px;
      }
  }

```
# js
```


```
