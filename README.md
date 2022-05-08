# Form
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML / FORMS</title>
    <style>
        form,h1{
            padding-left: 40%;
        }
    </style>
</head>

<body>
    <h1>Forms :</h1>

    <form action="./sign-in.html" method="post">
        <div>
            <label for="fn">Full name : </label> <br>
            <input id="fn" type="text" placeholder="Enter Full Name" maxlength="10" minlength="3" required name="fullname">
        </div>

        <br>

        <div>
            <label for="Pwd">Password : </label>  <br>
            <input required name="password" id="Pwd" type="Password" placeholder="Enter Password" maxlength="8" minlength="6">
        </div>
        <br>

        <div>
            <label >Number : </label>  <br>
            <input  name="count"  type="number" placeholder="Number" max="10" min="0">
        </div>

        <br>

        <div>
            <label>Email : </label>  <br>
            <input required name="Email"  type="email" placeholder="Enter email">
        </div>

        <br>

        <div>
            <label >Search </label>  <br>
            <input  name="Search" type="search" placeholder="Search" >
        </div>

        <br>
        <div>
            <label >date </label>  <br>
            <input  name="date" type="date" >
        </div>

        <br>

        <div>
            <input id="c" required  name="check" type="checkbox" >
            <label for="c" >I accept terms and condition </label> 
            
        </div>

        <br>

        <div>
            <input  name="gender" type="radio">
            <label for="" >Male </label>  

            <input  name="gender" type="radio">
            <label for="" >Female </label>  
       
            <input  name="gender" type="radio">
            <label for="" >Others </label> 
            
        </div>

        <br>

        <div>
            <p>STATE : </p>
                <input list="states" type="text" placeholder="state.......">

                <datalist id="states">
                    <option value="KARNATAKA">KARNATAKA</option>
                    <option value="TAMILNADU">TAMILNADU</option>
                    <option value="KERALA">KERALA</option>
                    <option value="MAHARASHTRA">MAHARASHTRA</option>
                    <option value="GOA">GOA</option>
                    <option value="ANDRA PRADESH">ANDRA PRADESH</option>
                    <option value="PUNE">PUNE</option>
                </datalist>
        </div>
        <br>
        <div>
                 <label>Select food : </label>
                 <select name="food" multiple>
                     <optgroup label="VEG">
                     <option value="Gobi">Gobi</option>
                     <option value="Palav">Palav</option>
                     <option value="Fried rice">Fried rice</option>
                     <option value="Lemon Rice">Lemon Rice</option>
                     <option value="Puliogare">Puliogare</option>
                     <option value="Idli Vada">Idli Vada</option>
                    </optgroup>

                    <optgroup label="NON-VEG">
                     <option value="Egg Rice">Egg Rice</option>
                     <option value="Chicken Kabab">Chicken Kabab</option>
                     <option value="Biriyani">Biriyani</option>
                    </optgroup>

        </select>
        </div>

        <br>

            <textarea placeholder="Write something .............." name="feedback" id="" cols="60" rows="10"></textarea>

        <br>

        <div>
            <!-- <input type="submit" value="Sign-In"> -->
            <button type="submit">Sign Up</button>
        </div>
        <br>
        <div>
            <!-- <input type="submit" value="Sign-In"> -->
            <button type="reset">Reset</button>
        </div>


    </form>

    </form>
</body>

</html>
