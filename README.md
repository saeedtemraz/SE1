# SE1
<!doctype html>
<html>
    <head>
        <style type="text/css">

            body {font-family:Arial, Sans-Serif;}

            #container {width:400px; margin:0 auto;}

            /* Nicely lines up the labels. */
            form label {display:inline-block; width:200px;}

            /* You could add a class to all the input boxes instead, if you like. That would be safer, and more backwards-compatible */
            form input[type="text"],
            form input[type="password"],
            form input[type="email"] {width:200px;}

            form .line {clear:both;}
            form .line.submit {text-align:right;}

        </style>
    </head>
    <body>
        <div id="container">
            <form>
                <h1>Register</h1>
                <div class="line"><label for="username">Username *: </label><input type="text" id="username" /></div>
                <div class="line"><label for="pwd">Password *: </label><input type="password" id="pwd" /></div>
                <!-- You may want to consider adding a "confirm" password box also -->
                <div class="line"><label for="surname">Surname *: </label><input type="text" id="surname" /></div>
                <div class="line"><label for="other_names">Other Names *: </label><input type="text" id="names" /></div>
                <div class="line"><label for="dob">Date of Birth *: </label><input type="text" id="dob" /></div>
                <div class="line"><label for="email">Email *: </label><input type="email" id="email" /></div>
                <!-- Valid input types: http://www.w3schools.com/html5/html5_form_input_types.asp -->
                <div class="line"><label for="tel">Telephone: </label><input type="text" id="tel" /></div>
                <div class="line"><label for="add">Address *: </label><input type="text" id="add" /></div>
                <div class="line"><label for="ptc">Post Code *: </label><input type="text" id="ptc" /></div>
                <div class="line submit"><input type="submit" value="Submit" /></div>
                 <A HREF="C:/Users/111372/Desktop/login.html">login</A>
              

                <p>Note: Please make sure your details are correct before submitting form and that all fields marked with * are completed!.</p>
            </form>
        </div>
    </body>
</html>
