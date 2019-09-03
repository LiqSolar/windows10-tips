# Windows 10 Tips

## Open command window here

1. Add Open Command Prompt window here option to the right-click context menu in Windows 10.

    show-opencmdhere.reg

        Windows Registry Editor Version 5.00
    
        [HKEY_CLASSES_ROOT\Directory\Background\shell\cmd]
        "ShowBasedOnVelocityId"=dword:00639bc8
        "HideBasedOnVelocityId"=-

2. Delete Open Command Prompt window here option from the right-click context menu in Windows 10.

    hide-opencmdhere.reg

        Windows Registry Editor Version 5.00
        
        [HKEY_CLASSES_ROOT\Directory\Background\shell\cmd]
        "HideBasedOnVelocityId"=dword:00639bc8
        "ShowBasedOnVelocityId"=-
