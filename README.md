# ShadowHound  

This is a project I am working on to parse through sharphound data using commmand line jq queries instead of using bloodhound.  
My goal is to replicate a lot of the functionality of bloodhound and put it in command line format.  

Implemented Features:  

Users:
<ul>  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Show All Users  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Show All Enabled Users  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Show All Disabled Users  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Show Enabled Users with Descriptions  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Show Disabled Users with Descripts  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Last Login  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;No Login Since Before Password Reset  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Kerberoastable Accounts  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;User Permissions  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Domain Admin Accounts         
        </ul>
Computers  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Show all Operating Systems  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Find Computers with Unsupported Operating Systems  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Show Last Time Computer Powered On  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;What Computers were Logged In Within ___ Days  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Computer Permissions  
        
Groups  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Group Permissions  
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Find Principals with DCSync Rights  
       
