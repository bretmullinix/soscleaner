 Must be done as root.
 
 1.  download the files from github to the /home/bmullinix folder.  Make sure you replace the /home/bmullinix with your full path prefix in step 4 for it to work.

  2. create a virtual enviroment.  the code to create one for python 2.7 is "virtualenv venv"

  3. activate the virtual enviroment (source venv/bin/activate)

  4. pip install --no-index --find-links /home/bmullinix/content/var/www/packages /home/bmullinix/content/var/www/packages/soscleaner-0.4.4.tar.gz

