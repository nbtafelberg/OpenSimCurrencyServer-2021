So this guy did amazing work I'm going to do the php file and then put it here.


# OpenSimCurrencyServer 2021 - 911
For the new OpeSimulator 0.9.2.1 DEV

DTL/NSL Money Server by Fumi.Iseki and NSL http://www.nsl.tuis.ac.jp , here is my test revision.

    This is currently being tested with:
    opensim-0.9.2.1 Dev - 50 target vs2019 mono 6.xx.x
    Status works.
    Test Grid: http://openmanniland.de:8002/
    Viewer link: secondlife://http|!!openmanniland.de|8002+Welcome
    
## Test OpenSimulator binary include MoneyServer and ossl script example 
### Download: 
binary testfiles Ubuntu 18 + Scripts + Money + landtool:  https://www.mediafire.com/file/9v2y3ifg40mkph7/opensim-0.9.2.1.50.zip/file
 
## copy:

copy addon-modules to addon-modules

copy bin to bin

copy helper to web (www/html/helper) - work in progress

    landtool.php works please insert the MySQL data in the landtool.php file. 
    This landtool.php version is standalone.
    currency.php work in progress.

## Building:

### Linux: (Ubuntu 18.04 test server)

    chmod +x runprebuild19.sh
    ./runprebuild19.sh
    msbuild /p:Configuration=Release

### Windows: (Windows 10, Visual Studio 2019 Community)

    runprebuild19.bat
    start Visual studio with OpenSim.sln 
    or run compile.bat
    
Config: Robust, MoneyServer and OpenSim.

Start: 1. Robust, 2. MoneyServer, 3. OpenSim regions.

INFO: On Windows and Visual Studio, the Money Server only starts when mysql is running and config is set.
