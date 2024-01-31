 <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Advance Form</title>
</head>

<body>
    <form style="margin: 5%;">
        <fieldset>
            <legend>
                Advance Form Using HTML:5
            </legend>
            
            Color:
            <input type="color" name="Color" />
            <br><br>
            Name:
            <input type="text" name="Name" required="" autofocus=""/>
            <br><br>
            Email:
            <input type="email" name="email" required="" autofocus=""/>
            <br><br>
            Password:
            <input type="password" name="password" autofocus=""/>
            <br><br>
            Age:
            <input type="number" autodocus />
            <br><br>
            Gender:
            <input type="radio" name="gender" autofocus/>Male
            <input type="radio" name="gender" autofocus/>Female
            
             <br><br>
Courses:
<input type="text" name="courses" autofocus  list="course"/>
<datalist id="course">
    <option value="Cricket">Cricket</option>
    <option value="Footbal">Footbal</option>
    <option value="Badminton">Badminton</option>
    <option value="Volleyvall">Volleyvall</option>
    
    </datalist>



            <br><br>
            <input type="submit" name="submit"></fieldset>
    </form>

</body>

</html>
