### Описание работы Patroni


#### Каталоги и файлы Patroni (ver.2.1.3) при установке Patroni из под пользователя root
***/usr/local/bin или /usr/bin*** - каталог размещения бинарных файлов Patroni

Файлы размещенные в данном каталоге:

        -rwxr-xr-x 1 root root 219 May  5 18:53 patroni
        -rwxr-xr-x 1 root root 222 May  5 18:53 patroni_aws
        -rwxr-xr-x 1 root root 212 May  5 18:53 patronictl
        -rwxr-xr-x 1 root root 226 May  5 18:53 patroni_raft_controller
        -rwxr-xr-x 1 root root 231 May  5 18:53 patroni_wale_restore

***/usr/local/lib64/python3.6/site-packages/*** - каталог 64 bit библиотек используемых для работы Patroni 

Файлы размещенные в данном каталоге:

        drwxr-xr-x  4 root root  328 May  5 18:47 psutil
        drwxr-xr-x  2 root root  157 May  5 18:47 psutil-5.9.0-py3.6.egg-info
        drwxr-xr-x  3 root root  264 May  5 18:47 psycopg2
        drwxr-xr-x  2 root root  119 May  5 18:47 psycopg2_binary-2.9.3.dist-info
        drwxr-xr-x  2 root root 4096 May  5 18:47 psycopg2_binary.libs
        drwxr-xr-x  2 root root  102 May  5 18:47 PyYAML-6.0.dist-info
        drwxr-xr-x  3 root root 4096 May  5 18:47 yaml
        drwxr-xr-x  3 root root   44 May  5 18:47 _yaml
        
***/usr/local/lib/python3.6/site-packages/***  - каталог библиотек используемых для работы Patroni

Файлы размещенные в данном каталоге:

        drwxr-xr-x 31 root root   4096 May  5 17:29 .
        drwxr-xr-x  3 root root     27 May  5 17:23 ..
        drwxr-xr-x  3 root root   4096 May  5 17:29 click
        drwxr-xr-x  2 root root    106 May  5 17:29 click-8.0.4.dist-info
        drwxr-xr-x  6 root root    210 May  5 17:29 dateutil
        drwxr-xr-x  3 root root     63 May  5 17:29 _distutils_hack
        -rw-r--r--  1 root root    152 May  5 17:29 distutils-precedence.pth
        drwxr-xr-x  4 root root   4096 May  5 17:29 dns
        drwxr-xr-x  2 root root     81 May  5 17:29 dnspython-2.2.1.dist-info
        drwxr-xr-x  4 root root    104 May  5 17:29 etcd
        drwxr-xr-x  3 root root    195 May  5 17:29 importlib_metadata
        drwxr-xr-x  2 root root    102 May  5 17:29 importlib_metadata-4.8.3.dist-info
        drwxr-xr-x  7 root root   4096 May  5 17:29 patroni
        drwxr-xr-x  2 root root    155 May  5 17:29 patroni-2.1.3.dist-info
        drwxr-xr-x  5 root root    111 May  5 17:29 pip
        drwxr-xr-x  2 root root    130 May  5 17:29 pip-21.3.1.dist-info
        drwxr-xr-x  6 root root     86 May  5 17:29 pkg_resources
        drwxr-xr-x  3 root root     66 May  5 17:29 prettytable
        drwxr-xr-x  2 root root    102 May  5 17:29 prettytable-2.5.0.dist-info
        drwxr-xr-x  2 root root    127 May  6 14:26 __pycache__
        drwxr-xr-x  2 root root    118 May  5 17:29 python_dateutil-2.8.2.dist-info
        drwxr-xr-x  2 root root    157 May  5 17:29 python_etcd-0.4.5-py3.6.egg-info
        drwxr-xr-x  7 root root   4096 May  5 17:29 setuptools
        drwxr-xr-x  2 root root    126 May  5 17:29 setuptools-59.6.0.dist-info
        drwxr-xr-x  2 root root    102 May  5 17:29 six-1.16.0.dist-info
        -rw-r--r--  1 root root  34549 May  5 17:29 six.py
        drwxr-xr-x  2 root root     81 May  5 17:29 typing_extensions-4.1.1.dist-info
        -rw-r--r--  1 root root 107685 May  5 17:29 typing_extensions.py
        drwxr-xr-x  6 root root    291 May  5 17:29 urllib3
        drwxr-xr-x  2 root root    106 May  5 17:29 urllib3-1.26.9.dist-info
        drwxr-xr-x  4 root root    164 May  5 17:29 wcwidth
        drwxr-xr-x  2 root root    118 May  5 17:29 wcwidth-0.2.5.dist-info
        drwxr-xr-x  2 root root    117 May  5 17:29 ydiff-1.2-py3.6.egg-info
        -rw-r--r--  1 root root  34532 May  5 17:29 ydiff.py
        drwxr-xr-x  2 root root    102 May  5 17:29 zipp-3.6.0.dist-info
        -rw-r--r--  1 root root   8425 May  5 17:29 zipp.py

#### Каталоги и файлы Patroni (ver.2.1.4) при установке Patroni из под пользователя postgres

***~/.local/bin*** - каталог размещения бинарных файлов Patroni

Файлы размещенные в данном каталоге:

        drwxrwxr-x. 2 postgres postgres 167 июн 23 17:20 .
        drwx------. 5 postgres postgres  41 июн 23 17:18 ..
        -rwxrwxr-x. 1 postgres postgres 219 июн 23 17:18 patroni
        -rwxrwxr-x. 1 postgres postgres 222 июн 23 17:18 patroni_aws
        -rwxrwxr-x. 1 postgres postgres 212 июн 23 17:18 patronictl
        -rwxrwxr-x. 1 postgres postgres 226 июн 23 17:18 patroni_raft_controller
        -rwxrwxr-x. 1 postgres postgres 231 июн 23 17:18 patroni_wale_restore

***~/.local/lib/python3.6/site-packages*** - каталог библиотек используемых для работы Patroni

Файлы размещенные в данном каталоге:

        drwxrwxr-x.  3 postgres postgres   4096 июн 23 17:18 click
        drwxrwxr-x.  2 postgres postgres    106 июн 23 17:18 click-8.0.4.dist-info
        drwxrwxr-x.  6 postgres postgres    210 июн 23 17:18 dateutil
        drwxrwxr-x.  4 postgres postgres   4096 июн 23 17:18 dns
        drwxrwxr-x.  2 postgres postgres     81 июн 23 17:18 dnspython-2.2.1.dist-info
        drwxrwxr-x.  4 postgres postgres    104 июн 23 17:18 etcd
        drwxrwxr-x.  3 postgres postgres    195 июн 23 17:18 importlib_metadata
        drwxrwxr-x.  2 postgres postgres    102 июн 23 17:18 importlib_metadata-4.8.3.dist-info
        drwxrwxr-x.  7 postgres postgres   4096 июн 23 17:18 patroni
        drwxrwxr-x.  2 postgres postgres    155 июн 23 17:18 patroni-2.1.4.dist-info
        drwxrwxr-x.  5 postgres postgres    111 июн 23 17:20 pip
        drwxrwxr-x.  2 postgres postgres    130 июн 23 17:20 pip-21.3.1.dist-info
        drwxrwxr-x.  3 postgres postgres     66 июн 23 17:18 prettytable
        drwxrwxr-x.  2 postgres postgres    102 июн 23 17:18 prettytable-2.5.0.dist-info
        drwxrwxr-x.  4 postgres postgres   4096 июн 23 17:18 psutil
        drwxrwxr-x.  2 postgres postgres    157 июн 23 17:18 psutil-5.9.1-py3.6.egg-info
        drwxrwxr-x.  3 postgres postgres    264 июн 23 17:23 psycopg2
        drwxrwxr-x.  2 postgres postgres    119 июн 23 17:23 psycopg2_binary-2.9.3.dist-info
        drwxrwxr-x.  2 postgres postgres   4096 июн 23 17:23 psycopg2_binary.libs
        drwxrwxr-x.  2 postgres postgres    127 июн 23 17:18 __pycache__
        drwxrwxr-x.  2 postgres postgres    118 июн 23 17:18 python_dateutil-2.8.2.dist-info
        drwxrwxr-x.  2 postgres postgres    157 июн 23 17:18 python_etcd-0.4.5-py3.6.egg-info
        drwxrwxr-x.  2 postgres postgres    102 июн 23 17:18 PyYAML-6.0.dist-info
        drwxrwxr-x.  2 postgres postgres    102 июн 23 17:18 six-1.16.0.dist-info
        -rw-rw-r--.  1 postgres postgres  34549 июн 23 17:18 six.py
        drwxrwxr-x.  2 postgres postgres     81 июн 23 17:18 typing_extensions-4.1.1.dist-info
        -rw-rw-r--.  1 postgres postgres 107685 июн 23 17:18 typing_extensions.py
        drwxrwxr-x.  6 postgres postgres   4096 июн 23 17:18 urllib3
        drwxrwxr-x.  2 postgres postgres    106 июн 23 17:18 urllib3-1.26.9.dist-info
        drwxrwxr-x.  4 postgres postgres    164 июн 23 17:18 wcwidth
        drwxrwxr-x.  2 postgres postgres    118 июн 23 17:18 wcwidth-0.2.5.dist-info
        drwxrwxr-x.  3 postgres postgres   4096 июн 23 17:18 yaml
        drwxrwxr-x.  3 postgres postgres     44 июн 23 17:18 _yaml
        drwxrwxr-x.  2 postgres postgres    117 июн 23 17:18 ydiff-1.2-py3.6.egg-info
        -rw-rw-r--.  1 postgres postgres  34532 авг  8  2020 ydiff.py
        drwxrwxr-x.  2 postgres postgres    102 июн 23 17:18 zipp-3.6.0.dist-info
        -rw-rw-r--.  1 postgres postgres   8425 июн 23 17:18 zipp.py

Пакеты необходимые для Patroni.

        [root@vdc01-piupddbn1 bin]# python3.6 -m pip list
         Package            Version
         ------------------ -------
         click              8.0.4
         dnspython          2.2.1
         importlib-metadata 4.8.3
         patroni            2.1.3
         pip                21.3.1
         prettytable        2.5.0
         psutil             5.9.0
         psycopg2-binary    2.9.3
         python-dateutil    2.8.2
         python-etcd        0.4.5
         PyYAML             6.0
         setuptools         59.6.0
         six                1.16.0
         typing_extensions  4.1.1
         urllib3            1.26.9
         wcwidth            0.2.5
         ydiff              1.2
         zipp               3.6.0
