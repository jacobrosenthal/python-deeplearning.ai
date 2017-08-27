# deeplearning.ai coursework

My coursework pulled from [Andrew NGs deeplearning.ai course](https://www.coursera.org/specializations/deep-learning). If the homework looks at all interesting to you, I highly recommend you enroll. I got a lot out of it and am eagerly awaiting new courses.

<details><summary>At the time of pulling these files, their environment reported the following versions:</summary><p>

```
! python --version
Python 3.6.0 :: Anaconda custom (64-bit)
! pip freeze
	alabaster==0.7.9
	alembic==0.9.5
	anaconda-client==1.6.0
	anaconda-navigator==1.5
	anaconda-project==0.4.1
	astroid==1.4.9
	astropy==1.3
	atari-py==0.1.1
	Babel==2.3.4
	backports.shutil-get-terminal-size==1.0.0
	backports.weakref==1.0rc1
	beautifulsoup4==4.5.3
	bitarray==0.8.1
	blaze==0.10.1
	bleach==1.5.0
	bokeh==0.12.4
	boto==2.45.0
	Bottleneck==1.2.0
	cffi==1.9.1
	chardet==2.3.0
	chest==0.2.3
	click==6.7
	cloudpickle==0.2.2
	clyent==1.2.2
	colorama==0.3.7
	conda==4.3.14
	configobj==5.0.6
	contextlib2==0.5.4
	cryptography==1.7.1
	cycler==0.10.0
	Cython==0.25.2
	cytoolz==0.8.2
	dask==0.13.0
	datashape==0.5.4
	decorator==4.0.11
	dill==0.2.5
	docutils==0.13.1
	et-xmlfile==1.0.1
	fastcache==1.0.2
	Flask==0.12
	Flask-Cors==3.0.2
	gevent==1.2.1
	greenlet==0.4.11
	gym==0.9.2
	h5py==2.6.0
	HeapDict==1.0.0
	html5lib==0.9999999
	idna==2.2
	imagesize==0.7.1
	ipykernel==4.5.2
	ipython==5.1.0
	ipython-genutils==0.1.0
	ipywidgets==5.2.2
	isort==4.2.5
	itsdangerous==0.24
	jdcal==1.3
	jedi==0.9.0
	Jinja2==2.9.4
	jsonschema==2.5.1
	jupyter==1.0.0
	jupyter-client==4.4.0
	jupyter-console==5.0.0
	jupyter-core==4.2.1
	jupyterhub==0.7.2
	jupyterlab==0.18.1
	Keras==2.0.7
	lazy-object-proxy==1.2.2
	llvmlite==0.15.0
	locket==0.2.0
	lxml==3.7.2
	Mako==1.0.7
	Markdown==2.6.8
	MarkupSafe==0.23
	matplotlib==2.0.0
	mistune==0.7.3
	mpmath==0.19
	multipledispatch==0.4.9
	nbconvert==4.2.0
	nbformat==4.2.0
	networkx==1.11
	nltk==3.2.2
	nose==1.3.7
	notebook==5.0.0
	numba==0.30.1
	numexpr==2.6.1
	numpy==1.11.3
	numpydoc==0.6.0
	odo==0.5.0
	olefile==0.44
	openpyxl==2.4.1
	pamela==0.3.0
	pandas==0.19.2
	partd==0.3.7
	pathlib2==2.2.0
	patsy==0.4.1
	pdb==0.1
	pep8==1.7.0
	pexpect==4.2.1
	pickleshare==0.7.4
	Pillow==4.0.0
	ply==3.9
	prompt-toolkit==1.0.9
	protobuf==3.3.0
	psutil==5.0.1
	ptyprocess==0.5.1
	py==1.4.32
	pyasn1==0.1.9
	pycosat==0.6.1
	pycparser==2.17
	pycrypto==2.6.1
	pycurl==7.43.0
	pyflakes==1.5.0
	pyglet==1.2.4
	Pygments==2.1.3
	pygraphviz==1.3.1
	pylint==1.6.4
	PyOpenGL==3.1.0
	pyOpenSSL==16.2.0
	pyparsing==2.1.4
	pytest==3.0.5
	python-dateutil==2.6.0
	python-editor==1.0.3
	python-gnupg==0.4.1
	pytz==2016.10
	PyYAML==3.12
	pyzmq==16.0.2
	QtAwesome==0.4.3
	qtconsole==4.2.1
	QtPy==1.2.1
	redis==2.10.5
	requests==2.12.4
	rope-py3k==0.9.4.post1
	scikit-image==0.12.3
	scikit-learn==0.18.1
	scipy==0.18.1
	seaborn==0.7.1
	simplegeneric==0.8.1
	singledispatch==3.4.0.3
	six==1.10.0
	sklearn==0.0
	snowballstemmer==1.2.1
	sockjs-tornado==1.0.3
	Sphinx==1.5.1
	spyder==3.1.2
	SQLAlchemy==1.1.5
	statsmodels==0.6.1
	sympy==1.0
	tables==3.3.0
	tensorflow==1.2.1
	terminado==0.6
	Theano==0.9.0
	toolz==0.8.2
	torch==0.1.12.post2
	torchvision==0.1.8
	tornado==4.4.2
	traitlets==4.3.1
	unicodecsv==0.14.1
	wcwidth==0.1.7
	Werkzeug==0.11.15
	widgetsnbextension==1.2.6
	wrapt==1.10.8
	xlrd==1.0.0
	XlsxWriter==0.9.6
	xlwt==1.2.0
```

</p></details>

# Install
* Install [miniconda](https://conda.io/miniconda.html)
* Install [jupyter notebooks](http://jupyter.org/install.html)
* Create python3 environment with ```conda create -n py36 anaconda python=3```
* Install anything missing at the version required if necessary ```pip3 install numpy==1.11.3``` 
* Clone this repo ```git clone git@github.com:jacobrosenthal/python-deeplearning.ai.git```


# Run
* ```cd python-deeplearning.ai```
* Enable that environment (might be necessary every new session)```source activate py36```
* Open jupyter and select a homework assignment ```jupyter notebook .```


# Errata
These files were pulled from within a Coursera session with this script:
```
import zipfile
import os

def zipdir(path, ziph):
    # ziph is zipfile handle
    for root, dirs, files in os.walk(path):
        for file in files:
            ziph.write(os.path.join(root, file))

zf = zipfile.ZipFile('../../homework.zip', mode='w')

try:
    zipdir('../../', zf)

finally:

    zf.close()
```
