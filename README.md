Windows printing.

See http://godoc.org/github.com/alexbrainman/printer for details.

fork from : https://github.com/alexbrainman/printer 

add same job future (base on SetJob):

```
   #see:  https://docs.microsoft.com/en-us/windows/win32/printdocs/setjob

   DeleteJob
   PauseJob   
   CancelJob
   ResumeJob
   RestartJob
   LastPageEjectedJob
   SendToPrinterJob
      
   ReleaseJob
   RetainJob
```