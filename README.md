# source code reading notes

(1) Mar 11 2023
* the entry of v2ray application is actully at main folder.
* V2ray.go有 New方法，config.go有loadconfig方法.

(2) Mar 16 2023
* at main.go, base.RegisterCommand, then base.Execute, so we need to  go to folder main/commands/base  to see what happens.
* at execute.go, there is Execute(), this shows what happens. 
