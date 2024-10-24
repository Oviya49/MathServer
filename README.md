# Ex.05 Design a Website for Server Side Processing
## Date:24-10-2024

## AIM:
To design a website to find surface area of a Right Cylinder in server side.

## FORMULA:
Surface Area = 2Πrh + 2Πr<sup>2</sup>
<br>r --> Radius of Right Cylinder
<br>h --> Height of Right Cylinder

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
DEVELOPED BY: OVIYA N
REG.NO: 212223040140
```
```
<html>
    <head>
        <style>
            .box{
                border: 5px solid black;
                border-radius: 20px;
                width: 500px;
                height: 500px;
                background-color: peachpuff;
                padding: 10px;
                flex-direction: column;
                font-style: inherit;
                
            }
            input[type="text"]{
                font-size: larger;
                font-weight: 300;
                color: black;
                font-style: italic;
                
            }
            input[type="button"]{
                font-size: larger;
                font-weight: 200;
                color: blue;
                font-style: inherit;
            }
            body{
                display: flex;
                align-items: center;
                justify-content: center;
            }


        </style>
        <script>
            function calculatepower(){
                var a=Number(document.getElementById("CURRENT").value);
                var b=Number(document.getElementById("RESISTANCE").value);
                if(isNaN(a)||isNaN(b)||a==" "||b==" "){
                    document.getElementById("result").textContent="please enter a valid number!!";
                    return ;
                }
                var power = Math.pow(a, 2) * b;
                document.getElementById("result").textContent = "Power (P) = " + power + " watts";

            }
        </script>

    </head>
    <body background="https://img.freepik.com/free-photo/vivid-blurred-colorful-wallpaper-background_58702-3508.jpg?size=626&ext=jpg&ga=GA1.1.2113030492.1729468800&semt=ais_hybrid">
        <div class="box">
        <h1 align="center">CALCULATE THE POWER </h1>
        <h2 align="center">(OVIYA N)</h2>
        <br><br><br>
        <label>Current</label><br><br>
        <input type="text" id="CURRENT" placeholder="current in Amperes"><br><br>
        <label>Resistance</label><br><br>
        <input type="text" id="RESISTANCE" placeholder="Resistance in Ohms"><br><br>
        <input type="button" value="calculatePower" onclick="calculatepower()"><br><br>
        <p id="result"></p>
        </div>

    </body>
</html>
```



## HOMEPAGE:
![image](https://github.com/user-attachments/assets/fe3ee765-7cb1-4bc9-abc4-29942ad008d8)


## RESULT:
The program for performing server side processing is completed successfully.
