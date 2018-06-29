# LCE_PRM_Files
Custom LCE .prm files.

Tested with LCE Server 5.0.1

rsa_secureid_radius_authentication.prm parses RSA Secure ID RADIUS syslog events into Tenable LCE events.  

To use:
1.  Copy into the LCE plugins directory (/opt/lce/daemons/plugins)
2.  Restart lce_server and watch /opt/lce/admin/log/<YEAR><MON>.log for conflicts or errors.
