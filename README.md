<!DOCTYPE html>
<html>
 <head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0, shrink-to-fit=no">
  <title>Project</title>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  <style>
   			.class1 {
                      width: auto;
                      height: 80px;
                      background-color: grey;
                      color: white;
                      display: flex;
                      align-items: center;
					}

        .class1 a {
            
            text-decoration: none;
            color: white;
            margin: 10px;
            text-align: right;
			justify-content: flex-end;
			font-size:auto;
			padding:5px;
			
        }

        .class1 a:hover {
                         color: red;
						 border:solid;
						 radius:5px;
                         }
        .class2{
		        padding-top:0;
		        height:100%;
				width:auto;
				background-color:black;
               }	
        
        #h1{ 
             font-size:50px;
			 margin-left:10%;
			 font-family:arial;		
		     color:red;
		    }
		#p1{
		     margin-left:10%;
             right: 10%;
			 padding-top:10%;
             <!--transform: translate(-50%, -50%);-->
		     font-size:16px;
		     color:white;
		     font-family:arial;
		   }
		 #p2{
		     margin-left:10%;
             right: 10%;
			 top:5%;
            
		     font-size:16px;
		     color:white;
		     font-family:arial;
		   }
		    #button{
                         position: absolute;
                         top: 65%;
                         left: 50%;
                         transform: translate(-470%, -25%);
                         -ms-transform: translate(-50%, -50%);
                          background-color: black;
                          color: white;
                          font-size: 16px;
                          padding: 12px 24px;
                          border: none;
                          border-radius: 10px;
						  cursor:pointer;
		               }
  </style>
 </head>
 <body>
  <div class="class1">
  <h1> &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp  &nbsp &nbsp &nbsp &nbsp &nbsp CodeByMegha</h1>
        <a href="#">  &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp  &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp  &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp  &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp  &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp  &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp  Home</a> &nbsp;
        <a href="#">About</a> &nbsp;
        <a href="#">Skills</a> &nbsp;
        <a href="#">Projects</a> &nbsp;
		<a href="#">Contact</a> &nbsp;
  </div>
  <div class="class2">
   <p id="p1">Hi! I'm Megha Lund</p>
   <h1 id="h1">Front-End Developer</h1>
   <p id="p2">I'm a passionate developer dedicated to crafting user-friendly<br>
   experiences. I am focused, detail-oriented, and committed to<br>
   ensuring excellence in every project. Let's make something<br>
   special together.</p>
   <button type="button" id="button"  >Contact Me</button>
   
  </div>
  
 </body>
</html>
