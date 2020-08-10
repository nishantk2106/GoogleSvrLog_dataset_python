# GoogleSvrLog_dataset_python
Resource utilization is one of the key performance indicators for measuring the operational efficiency of cloud datacentres. Current cloud datacentres employ sophisticated task scheduling algorithms to improve resource utilization. The analysis of the algorithms is primarily based on analytical approaches. Due to the dynamicity and heterogeneity of cloud datacentre environment, the actual performance of the scheduling algorithms is often far beyond from the analytical results. Thus, it is important for researchers to be able to replay the historical operations on task placement and to offer a global view on the status of the cloud datacentre at any moment. In this project, we aim to provide a data-driven task placement replay simulation for cloud data centre, supported by big data technologies.

# Abstract 
Cloud computing has scalability, flexibility, and cost-effectiveness to meet emerging computing requirements. 
The characteristics of real workloads on a large production cloud cluster benefit not only cloud service providers but also researchers. 
This thesis presents a novel way to understand resource utilization in large-scale data centers. 
Current cloud datacentres employ sophisticated task scheduling algorithms to improve resource utilization. 
The analysis of the algorithms is primarily based on analytical approaches. 
Due to the dynamicity and heterogeneity of the cloud datacentre environment, the actual performance of the scheduling algorithms is often far beyond the analytical results.
Thus, researchers need to be able to replay the historical operations on task placement and to offer a global view on the status of the cloud datacentre at any moment.
Replay simulation is done using real-world server logs, i.e., Google cluster usage trace datasets. 
We demonstrate that the use of the simulation can greatly help researchers and system administrators to understand the behavior of the resources management schemes used in a given cloud computing environment.

# Author: Nishant Kumar


# list of dependencies :

channels:
•	defaults
•	conda-forge

Dependencies:
-	_libgcc_mutex=0.1=main
-	ca-certificates=2020.6.24=0
-	certifi=2018.8.24=py35_1
-	libedit=3.1.20191231=h7b6447c_0
-	libffi=3.2.1=hd88cf55_4
-	libgcc-ng=9.1.0=hdf63c60_0
-	libstdcxx-ng=9.1.0=hdf63c60_0
-	ncurses=6.2=he6710b0_1
-	nodejs=10.13.0=he6710b0_0
-	openssl=1.0.2u=h7b6447c_0
-	pip=10.0.1=py35_0
-	python=3.5.6=hc3d631a_0
-	readline=7.0=h7b6447c_5
-	setuptools=40.2.0=py35_0
-	sqlite=3.32.3=h62c20be_0
-	tk=8.6.10=hbc83047_0
-	wheel=0.31.1=py35_0
-	xz=5.2.5=h7b6447c_0
-	yarn=1.22.4=0
-	zlib=1.2.11=h7b6447c_3
pip:
-	backcall==0.2.0
-	decorator==4.4.2
-	ipykernel==5.3.1
-	ipython==7.9.0
-	ipython-genutils==0.2.0
-	jedi==0.17.1
-	jupyter-client==6.1.5
-	jupyter-core==4.6.3
-	numpy==1.18.5
-	pandas==0.25.3
-	parso==0.7.0
-	pexpect==4.8.0
-	pickleshare==0.7.5
-	prompt-toolkit==2.0.10
-	ptyprocess==0.6.0
-	py4j==0.10.7
-	pygments==2.6.1
-	pyspark==2.4.5
-	python-dateutil==2.8.1
-	pytz==2020.1
-	pyzmq==19.0.1
-	six==1.15.0
-	tornado==6.0.4
-	traitlets==4.3.3
-	wcwidth==0.2.5



# how to run the code :

create a enviornment in ICHEC server
Install the list of dependencies in enviornment
install Python 3.5 and Spark 2.3.3 to run the code using the pip command in enviornment.
To install spark there are some prerequisites that needs to be installed first that are : Scala and Java, These applications needs to be installed into the system where we are installing the spark.
Their are two options to install spark one is by source code and another one is packaged version. If we install source code then we have to build a source code and if we are installing packaged code then we simply use it.
After installing we have to unzip the tgz file by running the command: 
$tar xvf spark-xxx.tgz
After installing spark we have to create a virtual enviornment and install pyspark 2.4.5 into that enviornment by using command:
$pip install pyspark
After installing pyspark our enviornment is ready to run spark application we just have to import our .ipynb file into jupyterhub and can run that file.


