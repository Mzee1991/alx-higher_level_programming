# This is day 1 of my python journey
Write a Shell script that runs a Python script.
The Python file name will be saved in the environment variable $PYFILE

<div style="background-color: #333; color: #fff;">
mzee@ubuntu:~/py/0x00$ cat main.py 
#!/usr/bin/python3
print("Best School")

mzee@ubuntu:~/py/0x00$ export PYFILE=main.py
mzee@ubuntu:~/py/0x00$ ./0-run
Best School
mzee@ubuntu:~/py/0x00$
</div>
