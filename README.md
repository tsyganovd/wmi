wmi
===

Package wmi provides a WQL interface for WMI on Windows.

Change:

  24/03/2017
  
    Correctly return nil values. 
    string="<empty>"
    all int, uint and float = 0
    bool = false
