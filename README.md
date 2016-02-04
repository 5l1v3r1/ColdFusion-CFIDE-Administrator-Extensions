# CFIDE Administrator Custom Extensions
This repository contains custom extensions that extend the functionality of the ColdFusion CFIDE Administrator.

### Current Extensions
* Thread Tracker: Shows currently running threads with the ability to kill individual threads.  Adaptation to ColdFusion UI of functions created by [Upendra Roul] (http://coldfusion-tip.blogspot.com/2012/02/kill-coldfusion-thread-using-admin-api.html)
<img src="images/threads.png">
* Session Tracker: Shows currently active sessions. Adaptation to ColdFusion UI of functions created by David Crawford <dcrawford@acteksoft.com> with modifications by  Rob Brooks-Bilson <rbils@amkor.com> and Nathan Dintenfass
<img src="images/sessions.png">

### Installation 
Place the extensionscustom folder in your ColdFusion CFIDE Administrator directory; C:\ColdFusion11\cfusion\wwwroot\CFIDE\administrator\extensionscustom

Move the extensionscustom.cfm from the extensionscustom folder to the parent folder.
(optionally you can customize the custommenu.xml, but that is a different topic)