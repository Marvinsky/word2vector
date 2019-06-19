# word2vector

1.- Make sure the IMA contains all the libraries for Deep Learning

*  conda install pytorch

*  sudo python3 -m pip install -r requirements.txt

3.- jupyter notebook --generate-config.
	. sed -ie "s/#c.NotebookApp.ip = 'localhost'/#c.NotebookApp.ip = '*'/g" ~/.jupyter/jupyter_notebook_config.py

4.- Start Jupyter
	. jupyter notebook --ip=0.0.0.0 --no-browser

5.- Copy/paste this URL into your browser when you connect for the first time, to login with a token:
	. :8888/?token=
	. X.X.X.X:8888/?token=...
	. 

6.- Download data:

wget https://s3.amazonaws.com/video.udacity-data.com/topher/2018/October/5bbe6499_text8/text8.zip

7.- Verify volumen of IMA:

ubuntu@ip-172-31-30-53:~$ df -hT /dev/xvda1 
Filesystem     Type  Size  Used Avail Use% Mounted on
/dev/xvda1     ext4   97G   71G   27G  73% /
