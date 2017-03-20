### sources of info

- [github project](https://github.com/spotify/luigi)

- [getting started blogpost](https://marcobonzanini.com/2015/10/24/building-data-pipelines-with-python-and-luigi/)


### install

- my first env created by python 3...

        $ python3 -m venv /path/to/luigi_experimentation_stuff/env_luigi

        $ ls ./env_luigi/bin/
        total 80
        drwxr-xr-x  12 birkin  staff   408B Mar 20 16:55 ./
        drwxr-xr-x   6 birkin  staff   204B Mar 20 16:55 ../
        -rw-r--r--   1 birkin  staff   2.1K Mar 20 16:55 activate
        -rw-r--r--   1 birkin  staff   1.3K Mar 20 16:55 activate.csh
        -rw-r--r--   1 birkin  staff   2.4K Mar 20 16:55 activate.fish
        -rwxr-xr-x   1 birkin  staff   305B Mar 20 16:55 easy_install*
        -rwxr-xr-x   1 birkin  staff   305B Mar 20 16:55 easy_install-3.6*
        -rwxr-xr-x   1 birkin  staff   277B Mar 20 16:55 pip*
        -rwxr-xr-x   1 birkin  staff   277B Mar 20 16:55 pip3*
        -rwxr-xr-x   1 birkin  staff   277B Mar 20 16:55 pip3.6*
        lrwxr-xr-x   1 birkin  staff     7B Mar 20 16:55 python@ -> python3
        lrwxr-xr-x   1 birkin  staff    22B Mar 20 16:55 python3@ -> /usr/local/bin/python3`

- interesting, no `activate_this.py`

        $ pip install luigi
        Collecting luigi
          Downloading luigi-2.6.1.tar.gz (1.1MB)
            100% |████████████████████████████████| 1.1MB 255kB/s
        Collecting tornado<5,>=4.0 (from luigi)
          Downloading tornado-4.4.2.tar.gz (460kB)
            100% |████████████████████████████████| 460kB 1.4MB/s
        Collecting python-daemon<3.0 (from luigi)
          Downloading python_daemon-2.1.2-py2.py3-none-any.whl
        Collecting docutils (from python-daemon<3.0->luigi)
          Using cached docutils-0.13.1-py3-none-any.whl
        Requirement already satisfied: setuptools in ./env_luigi/lib/python3.6/site-packages (from python-daemon<3.0->luigi)
        Collecting lockfile>=0.10 (from python-daemon<3.0->luigi)
          Downloading lockfile-0.12.2-py2.py3-none-any.whl
        Installing collected packages: tornado, docutils, lockfile, python-daemon, luigi
          Running setup.py install for tornado ... done
          Running setup.py install for luigi ... done
        Successfully installed docutils-0.13.1 lockfile-0.12.2 luigi-2.6.1 python-daemon-2.1.2 tornado-4.4.2
