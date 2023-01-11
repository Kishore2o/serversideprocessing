# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:
Clone into serverside project

### Step 2:
Create a project inside the serverproject

### Step 3:
Create an app inside the serverproject


### Step 4:
Create an templates folder inside the serverapp 


### Step 5:
Create a folder inside the templates folder


### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>PERIMETER OF RECTANGLE</title>
        <style>
        form {
  width: 500px;
  margin: 0 auto;
  background-color : rgb(126, 78, 138);
  border: 1px solid #ccc;
  border-radius: 5px;
  padding: 20px;
}

label {
  display: block;
  font-size: 16px;
  font-weight: bold;
  margin-bottom: 10px;
}

input[type="text"],
input[type="number"] {
  width: 100%;
  padding: 12px 20px;
  margin-bottom: 20px;
  box-sizing: border-box;
  border: 1px solid #ccc;
  border-radius: 4px;
  resize: vertical;
}

input[type="submit"] {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  float: right;
}

input[type="submit"]:hover {
  background-color: #7c1053;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}

.perimeter {
  margin-bottom: 20px;
  color: black;
  font-size: 20px;
  font-weight: bold;
}
h1 {
  text-align: center;
  font-size: 24px;
  color: purple;
}
body {
    background-color:rgb(41, 2, 2);
}

</style>
    </head>
            <body>
                <h1> PERIMETER OF RECTANGLE </h1>
                 <form method="POST" action="/perimeter/">
                    {%csrf_token%}	
		 <label for="length">Enter Length</label>
         <input type="text" name="length" id="length" value="{{ length }}"/> <br>			
          <label for="width">Enter Width</label>
         <input type="width" name="width" id="width" value="{{ width }}"/><br>
          <input type="submit" value="Calculate Perimeter"/><br>

          <label for="perimeter">Perimeter</label>
         <input type="perimeter" name="perimeter" id="perimeter" value="{{ perimeter }}"/><br>
	</form>

            </body>
        
    
</html>
```

## OUTPUT:
![PERIMETER](https://user-images.githubusercontent.com/118679883/211867996-bf691b0c-c8b4-4201-809f-bb6a9fdadcdf.png)


### Home Page:

![Homw page](https://user-images.githubusercontent.com/118679883/211868281-5b8a4395-f5a9-444b-8bd3-1b222b522b9f.png)

## Result:

