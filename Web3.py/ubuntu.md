# Ubuntu

Ubuntu 의 경우 16.04 기준으로 python 3.5.2 버전이 설치되어 있으므로 별도 anaconda 추가 설치 없이 CLI 환경에 익숙하다면 apt-get 을 통해 pip, ipython, jupyter 등 만 추가 설치해도 무방



그게 아니라면 Anaconda 공식 웹사이트를 통해 다운받은 `chmod +x Anaconda3-5.x.x-Linux-xxx_xx.sh` 명령 을 통해 실행 권한을 준 후 `./Anaconda3-5.1.0-Linux-x86_64.sh` 를 통해 실행시켜 설치해준다.



자동으로 bin path 가 등록되지 않으므로 anaconda 가 설치된 directory_path/bin 을 export 등에 포함시켜주거나, python, pip, ipython, jupyter-notebook 등만 별도로 alias 등을 설정하여 사용한다.

​	ex)   `PATH="$HOME/anaconda3/bin:$PATH"`



# web3.py 설치

`pip install web3==4.0.0` 명령을 통해 에러 없이 설치되는것을 확인한다. 