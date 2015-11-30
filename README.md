datatables.net riot component

## Usage


      <script type="text/javascript" src="https://cdn.jsdelivr.net/riot/2.3.11/riot+compiler.min.js"></script>
      <!-- riot datagrid includes -->
      <script type="text/javascript" src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
      <script type="text/javascript" src="https://cdn.datatables.net/1.10.10/js/jquery.dataTables.min.js"></script>

      <datatable></datatable>

      <script>
        riot.mount('datatable', {
          id:"flop",
          options:{
            order:[[1,"desc"]],
          },
          data:[{"name":"foo",age:12}] 
        });
      </script>

I decided not to bundle the CSS+JS for flexibility reasons.

