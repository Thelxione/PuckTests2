<html>
<head>
   <title> Guajome Puck</title>
   <meta charset="utf-8">
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
   <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
   <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>

   <style>
       h1 {
           text-align: center;
       }
   </style>
</head>
<body>
   <div class="container">

   <h1> Play with the puck! </h1>
   <p> Click on the buttons below to get a different effect! </p>
<script src="https://www.puck-js.com/puck.js"> </script>

<table class="table table-striped">
   <tr>
       <th> Red Light </th>
       <td> <button onclick="Puck.write('LED1.set();\n');"> On </button> </th>
       <td> <button onclick="Puck.write('LED1.reset();\n');"> Off </button> </th>
   </tr>

   <tr>
       <th> Green Light </th>
       <td> <button onclick="Puck.write('LED2.set();\n');"> On </button> </th>
       <td> <button onclick="Puck.write('LED2.reset();\n');"> Off </button> </th>
   </tr>

   <tr>
       <th> Blue Light </th>
       <td> <button onclick="Puck.write('LED3.set();\n');"> On </button> </th>
       <td> <button onclick="Puck.write('LED3.reset();\n');"> Off </button> </th>
   </tr>

   <tr>
       <th onclick="Puck.write('reset();\n');"> Reset</th>
   </tr>
</table>
</div>
</body>
</html>

