Original twitter post: https://twitter.com/subTee/status/1488916163388137477

target: odbcad32.exe

UAC bypass

create a new DLL project and past in the cmdshell.dll code and build. 

As noted here: https://twitter.com/fkadibs/status/1489001994220101649

You can execute the DLL by putting it in your %PATH%. 

If all works, you should get an administrator shell without a UAC prompt. 
