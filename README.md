<!DOCTYPE>
    <html>
        <head>
            <!--Get A-->
            <title>Taxi Magic</title>
            <meta name="xiaolong" content="IAMAWESOME"/>
            <link rel="stylesheet" type="text/css" href="taxi.css"/>
            <script type="text/javascript" src="taxi.js">
            </script>
        </head>
        <body>
            <header>
                <img src="taximagic.jpg"/>
            </header>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#service">Service</a></li>
                    <li><a href="#membership">Membership</a></li>
                    <li><a href="#map"></a></li>
                </ul>
            </nav>
            
            <section id="about">
                <h2>About the Taxi Magic</h2>
                <p> for Over 10 years</p>
                <p>We offered from LA to JFK</p>
            </section>
            <section id="service">
                <h2>Services</h2>
                <ul>
                    <li>
                        Transportation
                        <ul>
                            <li>pick up</li>
                            <li>drop off</li>
                            <li>wait in car</li>
                        </ul>
                    </li>
                    <li>
                        Entertainment
                        <li>Jokes</li>
                        <li>Magic Shows</li>
                        <li>Trickes</li>
                    </li>
                </ul>
            </section>
            <section id="map">
                <h2>Tax Magic Area Map</h2>
                <img src="mapNY.png"/>
            </section>
            <section id="membership">
                <h2>Membership</h2>
                <form id="memberForm" name="memberForm">
                    <fieldset id="forminfo">
                        <label for="unameLabel">User Name: </label>
                        <input type="text" id="uname" id="uname" required>
                        <label for="email">Email Address</label>
                        <input type="text" id="email" id="email" required>
                        <label for="ride">Rides per month</label>
                        <input type="text" id="ride" id="ride" onchange="clac()" required>
                        
                        
                        
                    </fieldset>
                    <fieldset id="button" name="button">
                        <button id="register" name="button1" type="button" onclick="membership()" >Register</button>
                    </field>
                </form>
            </section>
            <footer>
                Taxi Magic<br/> 123,New York<br/>Telephone 6464-894-1993<br/>
                
            </footer>
        </body>
    </html>
    
    
 
    

    
