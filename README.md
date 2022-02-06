# x_s4bv_discode

Here is a ServiceNow Application for scanning ServiceNow Applications, and presenting the results visually in the CMDB / Business Service Map

Identify and understand the interconnectivity between an application's component parts, with extensible scanner API , you can build your own scans


WARNING: Use at your own risk. You may find things you never knew exist! 


# How to add a new scanner

Create a copy of the Scanner + ScannerBase APIs and name them according to Discode standard

These must retain their core .run() method 

Add new API definition to the application properties

# How to modify properties

