<ul>
<li>Click on the red certificate error message to view the failing certificate</li>
<li>Click on View Certificate</li>
<li>View details and click on Export selected certificate (any location, foo.crt)</li>
<li>Start a cmd shell and type the command "certmgr.msc" to open the certificate wizard</li>
<li>Click on <strong>Trusted Root Certification Authorities</strong> directory</li>
<li>Right click -> All task -> import</li>
<li>A popup window will appear asking for the "Store Location" Select Current User or Local Machine. Click Next</li>
<li>A new popup window will appear asking for the File Name: Browse and select your exported certificate file, foo.crt and Click Open</li>
<li>The popup should now display the full path to your certificate file, foo.crt. Click Next.</li>
<li>You should get a "import successful" message.</li>
<li>Close the import wizard application and try the URL again in the EDGE browser. If this worked you will not get the certificate error and the page will load normally</li>
</ul>