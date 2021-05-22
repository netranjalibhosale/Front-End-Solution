# Front-End-Solution
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
            color: white;
            display:inline-table;
            background-color:rgba(241, 120, 6, 0.842);
            width: 30px;
            border: 15px solid rgba(241, 120, 6, 0.842);
            padding: 5px;
            margin: 5px;
        }
        body{
            background-color:rgb(17, 129, 204);
            text-align: center;
        }
        input{
            background-color: rgb(17, 129, 204);
        }
        ::placeholder{
            color: white;
            text-decoration: underline;
        }
        label{
            color: white;
            text-decoration: underline;
            
        }
        button:hover{
            background-color: blue;
            color: white;
        }
        img {
            position:absolute;
            float: inline-start;
        }
        option{
            color:rgb(17, 129, 204); 
            
        }
   
      
    </style>
</head>
<body>
    <div>
    <h1 >Tell us about yourself</h1><img src = profile.png style="width: 80px ;height: 80px;" > 
    </div>
    <form > <label for="firstname" ></label><br> 
        <input name="firstname" id="firstname" placeholder="First Name" pattern="[A-Za-z0-9]+"> 
    </form>
    <form> <label for="lastname"></label><br> 
        <input name="lastname" id="lastname"placeholder="Last Name" pattern="[A-Za-z0-9]+"> 
    </form>

    <form> <label for="dob" ></label><br> 
        <input name="dob" id="dob"placeholder="Date of Birth" pattern="(0[1-9]|1[0-9]|2[0-9]|3[01])/(0[1-9]|1[012])/[0-9]{4}"> 
    </form>

    <label for="gender"></label>
    <select name="gender" placeholder="Gender" id="gender">
    <option value="select">Gender</option>    
    <option value="male">Male</option>
    <option value="female">Female</option>
    </select>

    <form> <label for="pincode"></label><br> 
        <input name="pincode"placeholder="Pincode" id="pincode" pattern="[0-9]"> 
    </form>

    <label for="phone"></label>
    <input type="tel" id="phone" name="phone"placeholder="Emergency contact number" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"><br>

    <label>Blood Group</label>
    <select name="bloodgrp" id="bloodgrp">
    <option>Select</option>    
    <option>A+</option>
    <option>A-</option>
    <option>B+</option>
    <option>B-</option>
    <option>AB+</option>
    <option>AB-</option>
    <option>O+</option>
    <option>O-</option>
    </select><br>

    <label for="allergy"></label>
    <select name="allergy" id="allergy" placeholder="Allergies" >
    <option>Allergies</option>    
    <option>Cough</option>
    <option>Headache</option>
    <option>Breathlessness</option>
    <option>Sweating</option>
    <option>Fever</option>
    <option>Body Ache</option>
    <option>Chest Pain</option>
    <option>Heart Burn</option>
    <option>Nausea</option>
    <option>Dizziness</option>
    <option>Other</option>
    </select>
    <br>

    <label for="comor">Co-morbidities:</label>
    <select name="comor" id="comor">
    <option>Select</option>    
    <option>Male</option>
    <option>Female</option>
    </select><br>

    <button style="border-style: solid;">Create Profile</button>
</body>
</html>
