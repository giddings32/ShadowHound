# ShadowHound  

This is a project I am working on to parse through sharphound data using commmand line jq queries instead of using bloodhound.  
My goal is to replicate a lot of the functionality of bloodhound and put it in command line format.  

Implemented Features:  

Users:
        <ul><ul>
        <li>Show All Users  </li>
        <li>Show All Enabled Users  </li>
        <li>Show All Disabled Users  </li>
        <li>Show Enabled Users with Descriptions  </li>
        <li>Show Disabled Users with Descripts  </li>
        <li>Last Login  </li>
        <li>No Login Since Before Password Reset  </li>
        <li>Kerberoastable Accounts  </li>
        <li>User Permissions  </li>
        <li>Domain Admin Accounts  </li>
        </ul></ul>
    
Computers:
        <ul><ul>
        <li>Show all Operating Systems  </li>
        <li>Find Computers with Unsupported Operating Systems  </li>
        <li>Show Last Time Computer Powered On  </li>
        <li>What Computers were Logged In Within ___ Days  </li>
        <li>Computer Permissions  </li>
        </ul></ul>
Groups:
        <ul><ul>
        <li>Group Permissions  </li>
        <li>Find Principals with DCSync Rights  </li>
        </ul></ul>
