<html>
    <head>
        <title>
            Welcome
        </title>
        <script type="text/javascript">
        
            function validate()
            {
                var username=document.getElementById("username");
                var password=document.getElementById("password");
                if(username.value.length > 5  || username.value == "")
                {
                    alert("invalid!")
                    return false;
                }
                else
                {
                    true;
                }
                
            }

        </script>
    </head>
    <body>
        <form action="welcome.html" onsubmit="return validate()">
        <input type="text" id="username" placeholder="Enter Username">
        <br>
        <input type="password" id="password" placeholder="Enter Password">
        <br>
        <input type="submit" value="Login"></input>
        </form>
    </body>
</html>
