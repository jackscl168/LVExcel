# LVExcel
    LabVIEW Excel library based on NPOI
  Thanks for mattwhitlock's LVExcel.The LabVIEW project can run to read and write the .xlsx(.xls),but when I use the .xlsx file 
by the office 2010 or 2007.There are some problem :   
    1.If I read a office 2010's Excel file and add some data ,then save it and opened by Office told me the .xlsx broken.  
    2.If I creat a new workbooks and save it ,then It will add two line words like"It is using by code"（maybe more word,I forget it and lazy..）when I click the save button or ctrl+s.  
Hence,I know it's a 4 years old project, the NPOI dlls that the project includes are too old to support new Excel version's product.Anyway 
I add the  lasted dlls at the path ".\Resources\net40" which is copyed from the Nuget:  
 \<package id="NPOI" version="2.4.1" targetFramework="net40" />  
 \<package id="SharpZipLib" version="0.86.0" targetFramework="net40" />  
and three little application VIs.    
    There a bug when saving file.I will solve it.
