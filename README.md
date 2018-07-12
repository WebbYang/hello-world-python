# hello-world-python

This course will mention the following stuffs:
1. How to edit and execute python files on a remote server.
2. How to use an editor for python programming on a remote server.
3. How to use functions.
4. How to import modules.  

## Before we begin
To save the time for Anaconda installation, I've done it already.  
It simply needs to run the script by: `bash Anaconda3-5.2.0-Linux-x86_64.sh`  
During the installation, the path has been exported as the process we did for blast last time.  
So now we can to test some basic commands to check if conda has been properly installed.  
Try `conda info` and `conda list`.  

## Test a simple "Hello World" in Python
Please login and go to your own folder.  
Create a file `test.py` and write something with `print` command.  
We execute the file by `python test.py`.  
You should see the line you expect to print.  

## Try it for Jupyter Notebook  
Because there's no GUI support in the shell interface, if we call an editor remotely, it's unable to show. We need another way to open the editor in our own local machine.  
* For mac:  
`ssh -L 8000:localhost:8888 guest66@140.112.2.71`  
* For windows:  
If you are using Putty:
    1. Set your Putty session to Connection type **SSH**, type the ip and port as usual.  
![SSH ip setting](ip.png) 
    2. Find SSH tunnels setting such as:    
![SSH tunnel setting](tunnels.png)  
  
If you are using MobaXterm:  
![SSH mobaXterm setting](mobaX.png)
  
Enter your password to login.    
You won't need to type `jupyter notebook --no-browser` because we already called.    
Just for record. If you type the above command, you'll see the response like:  
![response for jupyter notebook command](tag.png)  
  
Then go to your local machine browser and type:  
`http://localhost:8000`  
![Before we enter the notebook](browser.png)
Copy the token: `db46b6cd426b4382a028f71ec9cbbe19ec0979f5148ce2f2`  
Paste to the required field then we can see what's inside!

## Let's start today's lesson!
Go to `python_workshop/day_2` and click `function_demo.ipynb`.
