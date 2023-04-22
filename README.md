# ShadowHound  

This is a project I am working on to parse through sharphound data using commmand line jq queries instead of using bloodhound.  
My goal is to replicate a lot of the functionality of bloodhound and put it in command line format.  

Implemented Features:  

Users:
        <ul><ul>
        Show All Users  
        Show All Enabled Users  
        Show All Disabled Users  
        Show Enabled Users with Descriptions  
        Show Disabled Users with Descripts  
        Last Login  
        No Login Since Before Password Reset  
        Kerberoastable Accounts  
        User Permissions  
        Domain Admin Accounts         
        </ul></ul>
Computers:
        <ul>
        Show all Operating Systems  
        Find Computers with Unsupported Operating Systems  
        Show Last Time Computer Powered On  
        What Computers were Logged In Within ___ Days  
        Computer Permissions  
        </ul>
Groups:
        <ul>
        Group Permissions  
        Find Principals with DCSync Rights  
        </ul>
