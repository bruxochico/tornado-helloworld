# tornado-helloworld

create a hello world in python using tornado

required:


Python >= 2.7

install python pip :

```$ apt-get install python-pip```

use pip install to install packages necessary for run this helloworld :

```$ pip install -r requirements.txt```

using the environment variable to set the port without having to make changes to the python code, change the line that this arrow the port of the application to that below :


```app.listen(os.environ['PORT'])```

done this, if you want to change the port of your application it will not be necessary to change the code, just change the environment variable that we set before, follow the command :

```$ export PORT=5000 ; echo $PORT```

attribute execute permissions for script before running :

```$ chmod +x helloworld.py```
 
Run script and access your ip at port you as set!

