# FreeDBDesignerWeb
Free Visual Database Designer on JQuery, JQueryUI and JS<br>
<br>
<h2>"DOCUMENTATION"</h2><br>
<br>
<h3>Global variables</h3>
<p>
<br>&nbsp;&nbsp;    dependencies  (array)
<br>&nbsp;&nbsp;    //  This variable is an array of dependencies like:
<br>&nbsp;&nbsp;      ```
<br>&nbsp;&nbsp;      dependence = {
<br>&nbsp;&nbsp;&nbsp;			  from:       //Primary Key Table
<br>&nbsp;&nbsp;&nbsp;			  fromitem:   //Primary Key Field
<br>&nbsp;&nbsp;&nbsp;			  to:         //Destination Table
<br>&nbsp;&nbsp;&nbsp;			  toitem:     //Destination Field
<br>&nbsp;&nbsp;      }
<br>&nbsp;&nbsp;      ```
<br>    currentTable  (string)
<br>    //  This variable is containing the current selected table (that red table)
<br>      
<br>    dataTypes     (array)
<br>    /*  This variable is an array with the data types that supported 
<br>    in destination MySQL Tool/Project where will do you use it */
<br>
<br>    canvas        (canvas) 
<br>    //  The variable with canvas.
</p>
<h3>Universal Functions</h3>
<p>
<br>    createTable('table_name')
<br>    //  Creates table with name 'table_name'
<br>      
<br>    createTableAndReturn('table_name')
<br>    //  Creates table with name 'table_name' and return true if allright 
<br>    
<br>    addValue('table_name')
<br>    //  Creates empty field in table 'table_name'
<br>    
<br>    createValue('table_name','field_name','field_type','field_size')
<br>    /*  Creates field name 'field_name' in table 'table_name' with 
<br>    data type 'field_type' and characted limit 'field_size' */
<br>    
<br>    getFields('table_name')
<br>    //  Returns fields array from table 'table_name'
<br>    ```
<br>    field = {
<br>      name:   //Field name
<br>      type:   //Field data type
<br>      size:   //Field character limit
<br>    }
<br>    ```
<br>    reorder(obj)
<br>    //  Brings the table object to the foreground and all other tables to the background
<br>    removeTable(obj)
<br>    //  Removes table object
<br>    removeField(obj)
<br>    //  Removes field object and dependencies including this field
</p>
    
