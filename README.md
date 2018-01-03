```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>CSS</title>
    <link href="https://fonts.googleapis.com/css?family=Kanit" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  
    <style>

        .car {
            width: 150px;
            height: 80px;
            background: green;
            position: relative;
            z-index: 99;
        }

        .wheel1 {
            width: 40px;
            height: 40px;
            background: #333;
            border-radius: 50%;
            position: absolute;
            bottom: -20px;
            left: 10px;
        }

        .wheel2 {
            width: 40px;
            height: 40px;
            background: #333;
            border-radius: 50%;
            position: absolute;
            bottom: -20px;
            right: 10px;
        }
   
        .window1 {
            top: 10px;
            left: 10px;
            width: 50px;
            height: 30px;
            position: absolute;
            background: white;
        }

        .window2 {
            top: 10px;
            right: 10px;
            width: 50px;
            height: 30px;
            position: absolute;
            background: white;
        }

        .line {
            width: 1px;
            height: 50px;
            background: #333;
            position: absolute;
            top: 10px;
            left: 50%;
        }

        .open1 {
            top: 45px;
            left: 30px;
            position: absolute;
            width: 10px;
            height: 2px;
            background: #fff;
        }

        .open2 {
            top: 45px;
            right: 30px;
            position: absolute;
            width: 10px;
            height: 2px;
            background: #fff;
        }

        .shadow {
            top: 10px;
            width: 150px;
            height: 20px;
            border-radius: 100%;
            background: rgb(216, 216, 216);
            position: relative;
        }

    </style>
    
</head>
<body>

    <div class="car">
        <div class="window1"></div>
        <div class="window2"></div>
        <div class="open1"></div>
        <div class="open2"></div>
        <div class="line"></div>
        <div class="wheel1"></div>
        <div class="wheel2"></div>
    </div>
    <div class="shadow"></div>
    

</body>
</html>
```
