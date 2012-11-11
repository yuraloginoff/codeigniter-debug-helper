codeigniter-debug-helper
========================

This is a little helper functions for debugging your CodeIgniter application.
This helper contains the following functions:  
*   printr (for preint_r())
*   vardump (for var_dump())

###Usage

Load a helper into your controller:
		$this->load->helper('debug');

Print your array in readable format:
		printr($myarray);
The function will print print_r($myarray) with <pre> tags to make the output readable.

Print readable dump information about your variable:
		vardump($myvar);
The function will print vardump($myvar) with <pre> tags to make the output readable.