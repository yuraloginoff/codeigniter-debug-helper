codeigniter-debug-helper
========================

###Description

This is a little helper functions for debugging your CodeIgniter application.
This helper contains the following functions:

*   printr (for print_r())
*   vardump (for var_dump())

###Usage

Load a helper into your controller:

    $this->load->helper('debug');

**printr()**  
Print your array in readable format - with usage of print_r():

    printr($myarray);
  
The function will print print_r($myarray) with PRE tags to make the output readable.

**vardump()**  
Print readable dump information about your variable - with usage of var_dump():
    
    vardump($myvar);
    
The function will print vardump($myvar) with PRE  tags to make the output readable.