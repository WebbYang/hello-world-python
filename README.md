# hello-world-python

This course will mention the following stuffs:
1. How to edit and execute python files on a remote server.
2. How to use an editor for python programming on a remote server.
3. How to use functions.
4. How to import modules.  

## Try it for Jupyter Notebook  
* For mac:  
`ssh -L 8000:localhost:8888 guest66@140.112.2.71`  
* For windows:  
Find SSH tunnels setting such as:  
![SSH tunnel setting](tunnels.png)  
  
As usual, enter your password to login. Go to your folder directory and type:  
`juptyer notebook --no-browser`  
You'll see the response:  
![response for jupyter notebook command](tag.png) 
Then go to your local machine browser and type:  
`http://localhost:8000`  
![Before we enter the notebook](browser.png)
Paste the highlight tag then we can see what's inside!

