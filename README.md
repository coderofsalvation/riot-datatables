datatables.net riot component

## Usage


    <html>
    <head>
      <script type="text/javascript" src="https://cdn.jsdelivr.net/riot/2.3.11/riot+compiler.min.js"></script>
      <!-- riot datagrid includes -->
      <script type="text/javascript" src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
      <script type="text/javascript" src="riot-datagrid.min.js"></script>
    </head>
    <body>

    <datagrid></datagrid>

    <script>riot.mount('datagrid', {jquery:true, order:[[1,"desc"]] } )</script>

    </body>
    </html>


