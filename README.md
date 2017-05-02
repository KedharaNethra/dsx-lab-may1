# collect the feedback for DSX Lab at SJSU conducted by IBM DSX Team on May 1, 2017

Please open an issue for a problem you face or bug you find. This can be usability issue or code issue. 

Download in  tar.gz  format instead - 
1.  Get all tar files on your laptop
Images:
Download
http://dsx-private-cloud.mybluemix.net/downloads/anaconda_with_spark-v2.tar.gz/v1
as anaconda_with_spark-v2.tar.gz
Download:
http://dsx-private-cloud.mybluemix.net/downloads/rstudio-server-v2.tar.gz/v1
as rstudio-server-v2.tar.gz
2.  Cd  to the following path:
    a.  For mac: 
    /Users/<username>/Library/Application Support/ibm-dsx-desktop/
    b.  For Windows:
    %APPDATA%\ibm-dsx-desktop\
3.  Add the file registry.ini with the following JSON content:
{
    "tarPath": "<directory to where you downloaded the tar files>"
}


