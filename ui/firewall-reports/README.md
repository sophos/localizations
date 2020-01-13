# Firewall-report
This subdirectory contains localizations for the English language file found in [the Firewall Reporting repo](https://git.cloud.sophos/projects/UI/repos/firewall-reports/browse/projects/library/src/assets/i18n/en-us.json).

Please pull that file every sprint and leave all non-English localizations in this directory.

The localizations can be either of two styles:

 * A "flat" style like this: 

      {  
    
        "common.action.allow": "Allow",  
        
        "common.action.deny": "Deny",  
        
        . . . etc. 
        
      }  
    
 * A "nested" style like this:

    {  
    
        "common": {
            "action": {
                "allow": "Allow",
                . . . etc
            },
            "add": "Add",
            . . . etc
    }


Either way, the Central build system can consume the file(s).

