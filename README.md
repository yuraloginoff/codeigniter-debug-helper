codeigniter-debug-helper
========================

This is a little helper functions for debugging your CodeIgniter application.
This helper contains the following functions:  
*   printr (for preint_r())
*   vardump (for var_dump())

###Usage

Load a helper into your controller:
<pre>$this->load->helper('debug');</pre>

Print your array in readable format:
<pre>printr($myarray);</pre>
The function will print print_r($myarray) with PRE tags to make the output readable.

Print readable dump information about your variable:
<pre>vardump($myvar);</pre>
The function will print vardump($myvar) with PRE  tags to make the output readable.