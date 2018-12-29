# FreeDBDesignerWeb
Free Visual Database Designer on JQuery, JQueryUI and JS<br>
<br>
<h2>"DOCUMENTATION"</h2><br>
<br>
<h3>Global variables</h3>
<pre>
    dependencies  (array)
    <pre style="color:#38d635">//  This variable is an array of dependencies like:</pre>
    ```
    dependence = {
        from:       //Primary Key Table
	fromitem:   //Primary Key Field
        to:         //Destination Table
        toitem:     //Destination Field
    }
    ```
    currentTable  (string)
    <pre style="color:#38d635">//  This variable is containing the current selected table (that red table)</pre>
      
    dataTypes     (array)
    <pre style="color:#38d635">/*  This variable is an array with the data types that supported 
    in destination MySQL Tool/Project where will do you use it */</pre>

    canvas        (canvas) 
    <pre style="color:#38d635">//  The variable with canvas.</pre>
</pre>
<h3>Universal Functions</h3>
<pre>
    createTable('table_name')
    //  Creates table with name 'table_name'
      
    createTableAndReturn('table_name')
    //  Creates table with name 'table_name' and return true if allright 
    
    addValue('table_name')
    //  Creates empty field in table 'table_name'
    
    createValue('table_name','field_name','field_type','field_size')
    /*  Creates field name 'field_name' in table 'table_name' with 
    data type 'field_type' and characted limit 'field_size' */
    
    getFields('table_name')
    //  Returns fields array from table 'table_name'
    ```
    field = {
        name:   //Field name
        type:   //Field data type
        size:   //Field character limit
    }
    ```
    reorder(obj)
    //  Brings the table object to the foreground and all other tables to the background
    removeTable(obj)
    //  Removes table object
    removeField(obj)
    //  Removes field object and dependencies including this field
</pre>
    
