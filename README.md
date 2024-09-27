<!DOCTYPE html>
<html>
    <head> <!-- creating parameters for the nav bar {ie: where it is placed on the page and how it will appear on the page} -->
        <style>  
            body { 
                margin: 0;
            }
            
            ul {
                
                list-style-type: none;
                margin: 0;
                padding: 0;
                width: 20%;
                background-color: #1063;
                position: fixed;
                height: 100%;
                overflow: auto;

            }

            li a {
                display: block;
                color: white;
                text-align: center;
                padding: 14px 16px;
                text-decoration:none;

            }

            li a.active {
                background-color: #04AA6D;
                color: white;
            }

            li a:hover:not(.active) {
                background-color: #1023;
                color: white;
            }
            

        </style>
    </head>
    <body>
        <!-- Nav Bar Categories-->
        <ul>
            <li><a href="Home">Home Page</a></li>
            <li><a href="About">About Me Page</a></li>
            <li><a href="Project">Project Page</a></li>
            <li><a href="Home">Contanct Page</a></li>
    </ul>
    </body>
</html>
