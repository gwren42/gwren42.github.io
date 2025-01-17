---
layout: home 
---
<html>
<head>
<style>

  img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}

div {
  height: 100px;
  line-height: 100px;
  text-align: center;
  border: 2px dashed #f69c55;
}

    .center1 {
          text-align: center;
          border: 3px solid green;
        }
    .p3 {
        font-family: "Lucida Console", "Courier New", monospace;
        }
    .container {
            display: grid;
            /* Enables grid layout */
            grid-template-columns: 1fr 1fr 1fr;
            /* Creates two equal-width columns */
            gap: 10px;
            /* Adds space between columns */
        }
   .column {
            padding: 10px;
            /* Adds padding inside each column */
        }

        .column:nth-child(1) {
            background-color: #f2f2f2;
            /* Light grey background for the first column */
        }

        .column:nth-child(2) {
            background-color: #e6e6e6;
            /* Slightly darker grey 
          background for the second column */
        }

        .column:nth-child(3) {
            background-color: #e6e6e6;
            /* Slightly darker grey 
          background for the third column */
        }
</style>

<body>
<img src="spbanner2.png" alt="Lisa Makes Stuff Banner" width="90%"><br>
<div class="center1">
   <font size="5"> <p class="p3">Nothing here yet</p></font>

  </div>
  
  
  <div class="container">
        <div class="column">
<img src="amere.png" alt="patience is bitter but the fruit is sweet" width="100%">
</div>
  <div class="column"><div class="center1">
   <font size="5"> <p class="p3">Nothing here yet</p></font>

  </div></div>
</div>

<div class="container">
        <div class="column">
<img src="tea.png" alt="tea cup and pants" width="30%">
        </div>
        <div class="column">
<img src="cloudwool.png" alt="wool looking like clouds on a blue background" width="30%" >
          </div>
        <div class="column">
<img src="verticalyarn.png" alt="Vertical strips of yarn" width="30%" >
        </div></div>
</body>
  </head>
  </html>
