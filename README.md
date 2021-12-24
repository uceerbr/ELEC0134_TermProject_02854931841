# ELEC0134 AMLS TERM PROJECT
Term project for ELEC0134 at UCL

Running the project script (https://github.com/uceerbr/ELEC0134_TermProject_02854931841/blob/main/AMLS_Term_Project.ipynb) requires the datasets (as provided in class) to be in the same directory in subfolders named accordingly trainingDataset and testDataset.
#
In this same folder are several text documents containing test results from running the project script under different conditions.  There was a bug in the headings of the binary confusion matrices that sometimes printed the headings of the multivariate cases (Gliom and Meningioma) instead of the desired binary headings (tumor or no tumor).  Please ignore those headers.  The numbers and the accuracy percentages are correct.

#
I ran the program in an environment that had these libraries installed:

_tflow_select             2.1.0                       gpu    anaconda

absl-py                   0.10.0                   py36_0    anaconda

aiohttp                   3.6.3            py36he774522_0    anaconda

alembic                   1.7.5                    pypi_0    pypi

argon2-cffi               21.1.0           py36h68aa20f_0    conda-forge

astor                     0.8.1                    py36_0    anaconda

async-timeout             3.0.1                    py36_0    anaconda

async_generator           1.10                       py_0    conda-forge

attrs                     20.2.0                     py_0    anaconda

backcall                  0.2.0              pyh9f0ad1d_0    conda-forge

backports                 1.0                        py_2    conda-forge

backports.functools_lru_cache 1.6.4              pyhd8ed1ab_0    conda-forge

bleach                    4.1.0              pyhd8ed1ab_0    conda-forge

blinker                   1.4                      py36_0    anaconda

brotlipy                  0.7.0           py36he774522_1000    anaconda

ca-certificates           2021.10.8            h5b45459_0    conda-forge

cachetools                4.1.1                      py_0    anaconda

certifi                   2021.5.30        py36ha15d459_0    conda-forge

certipy                   0.1.3                    pypi_0    pypi

cffi                      1.14.3           py36h7a1dbc1_0    anaconda

chardet                   3.0.4                 py36_1003    anaconda

click                     7.1.2                      py_0    anaconda

colorama                  0.4.4              pyh9f0ad1d_0    conda-forge

console_shortcut          0.1.1                         4

cryptography              3.1.1            py36h7a1dbc1_0    anaconda

cudatoolkit               10.1.243             h74a9793_0    anaconda

cudnn                     7.6.5                cuda10.1_0    anaconda

cycler                    0.11.0             pyhd8ed1ab_0    conda-forge

decorator                 5.1.0              pyhd8ed1ab_0    conda-forge

defusedxml                0.7.1              pyhd8ed1ab_0    conda-forge

dlib                      19.22.0          py36h9f2b841_0    conda-forge

entrypoints               0.3             pyhd8ed1ab_1003    conda-forge

freeglut                  3.2.1                h0e60522_2    conda-forge

freetype                  2.10.4               h546665d_1    conda-forge

gast                      0.2.2                    py36_0    anaconda

google-auth               1.22.1                     py_0    anaconda

google-auth-oauthlib      0.4.1                      py_2    anaconda

google-pasta              0.2.0                      py_0    anaconda

greenlet                  1.1.2                    pypi_0    pypi

grpcio                    1.31.0           py36he7da953_0    anaconda

h5py                      2.10.0           py36h5e291fa_0    anaconda

hdf5                      1.10.4               h7ebc959_0    anaconda

icc_rt                    2019.0.0             h0cc432a_1    anaconda

icu                       68.2                 h0e60522_0    conda-forge

idna                      2.10                       py_0    anaconda

idna_ssl                  1.1.0                    py36_0    anaconda

importlib-metadata        2.0.0                      py_1    anaconda

importlib-resources       5.4.0                    pypi_0    pypi

intel-openmp              2020.2                      254    anaconda

ipykernel                 5.5.5            py36hfacbf0b_0    conda-forge

ipython                   7.16.1           py36h7b2dad6_2    conda-forge

ipython_genutils          0.2.0                      py_1    conda-forge

ipywidgets                7.6.5              pyhd8ed1ab_0    conda-forge

jasper                    2.0.33               h77af90b_0    conda-forge

jedi                      0.17.2           py36ha15d459_1    conda-forge

jinja2                    3.0.3              pyhd8ed1ab_0    conda-forge

joblib                    1.1.0              pyhd8ed1ab_0    conda-forge

jpeg                      9d                   h8ffe710_0    conda-forge

jsonschema                4.1.2              pyhd8ed1ab_0    conda-forge

jupyter                   1.0.0            py36ha15d459_6    conda-forge

jupyter-telemetry         0.1.0                    pypi_0    pypi

jupyter_client            7.1.0              pyhd8ed1ab_0    conda-forge

jupyter_console           6.4.0              pyhd8ed1ab_0    conda-forge

jupyter_core              4.8.1            py36ha15d459_0    conda-forge

jupyterhub                2.0.0                    pypi_0    pypi

jupyterlab_pygments       0.1.2              pyh9f0ad1d_0    conda-forge

jupyterlab_widgets        1.0.2              pyhd8ed1ab_0    conda-forge

keras                     2.3.1            py36h21ff451_0    conda-forge

keras-applications        1.0.8                      py_1    anaconda

keras-preprocessing       1.1.0                      py_1    anaconda

kiwisolver                1.3.1            py36hd77b12b_0

lcms2                     2.12                 h2a16943_0    conda-forge

libblas                   3.9.0              12_win64_mkl    conda-forge

libcblas                  3.9.0              12_win64_mkl    conda-forge

libclang                  11.1.0          default_h5c34c98_1    conda-forge

libgpuarray               0.7.6             h8ffe710_1003    conda-forge

liblapack                 3.9.0              12_win64_mkl    conda-forge

liblapacke                3.9.0              12_win64_mkl    conda-forge

libopencv                 4.5.1            py36ha8f7756_0    conda-forge

libpng                    1.6.37               h1d00b33_2    conda-forge

libprotobuf               3.13.0.1             h200bbdf_0    anaconda

libsodium                 1.0.18               h8d14728_1    conda-forge

libtiff                   4.2.0                h0c97f57_3    conda-forge

libwebp-base              1.2.1                h8ffe710_0    conda-forge

lz4-c                     1.9.3                h8ffe710_1    conda-forge

m2w64-gcc-libgfortran     5.3.0                         6    conda-forge

m2w64-gcc-libs            5.3.0                         7    conda-forge

m2w64-gcc-libs-core       5.3.0                         7    conda-forge

m2w64-gmp                 6.1.0                         2    conda-forge

m2w64-libwinpthread-git   5.0.0.4634.697f757               2    conda-forge

mako                      1.1.6              pyhd8ed1ab_0    conda-forge

markdown                  3.3.2                    py36_0    anaconda

markupsafe                2.0.1            py36h68aa20f_0    conda-forge

matplotlib                3.2.2                         1    conda-forge

matplotlib-base           3.2.2            py36hfa737b6_1    conda-forge

mistune                   2.0.0              pyhd8ed1ab_0    conda-forge

mkl                       2021.4.0           h0e2418a_729    conda-forge

msys2-conda-epoch         20160418                      1    conda-forge

multidict                 4.7.6            py36he774522_1    anaconda

nbclient                  0.5.9              pyhd8ed1ab_0    conda-forge

nbconvert                 6.0.7            py36ha15d459_3    conda-forge

nbformat                  5.1.3              pyhd8ed1ab_0    conda-forge

nest-asyncio              1.5.4              pyhd8ed1ab_0    conda-forge

notebook                  6.3.0            py36ha15d459_0    conda-forge

numpy                     1.19.5           py36h4b40d73_2    conda-forge

oauthlib                  3.1.0                      py_0    anaconda

olefile                   0.46               pyh9f0ad1d_1    conda-forge

opencv                    4.5.1            py36ha15d459_0    conda-forge

openjpeg                  2.4.0                hb211442_1    conda-forge

openssl                   1.1.1l               h8ffe710_0    conda-forge

opt_einsum                3.1.0                      py_0    anaconda

packaging                 21.3               pyhd8ed1ab_0    conda-forge

pandas                    0.25.3           py36he350917_0    conda-forge

pandoc                    2.16.2               h8ffe710_0    conda-forge

pandocfilters             1.5.0              pyhd8ed1ab_0    conda-forge

parso                     0.7.1              pyh9f0ad1d_0    conda-forge

pickleshare               0.7.5                   py_1003    conda-forge

pillow                    8.2.0            py36h9cbe6be_1    conda-forge

pip                       21.3.1             pyhd8ed1ab_0    conda-forge

prometheus_client         0.12.0             pyhd8ed1ab_0    conda-forge

prompt-toolkit            3.0.23             pyha770c72_0    conda-forge

prompt_toolkit            3.0.23               hd8ed1ab_0    conda-forge

protobuf                  3.13.0.1         py36ha925a31_1    anaconda

psutil                    5.8.0                    pypi_0    pypi

py-opencv                 4.5.1            py36h7b2dad6_0    conda-forge

pyasn1                    0.4.8                      py_0    anaconda

pyasn1-modules            0.2.8                      py_0    anaconda

pycparser                 2.20                       py_2    anaconda

pygments                  2.10.0             pyhd8ed1ab_0    conda-forge

pygpu                     0.7.6           py36h6434af4_1002    conda-forge

pyjwt                     1.7.1                    py36_0    anaconda

pyopenssl                 19.1.0                     py_1    anaconda

pyparsing                 3.0.6              pyhd8ed1ab_0    conda-forge

pyqt                      5.12.3           py36ha15d459_7    conda-forge

pyqt-impl                 5.12.3           py36he2d232f_7    conda-forge

pyqt5-sip                 4.19.18          py36he2d232f_7    conda-forge

pyqtchart                 5.12             py36he2d232f_7    conda-forge

pyqtwebengine             5.12.1           py36he2d232f_7    conda-forge

pyreadline                2.1                      py36_1    anaconda

pyrsistent                0.17.3           py36h68aa20f_2    conda-forge

pysocks                   1.7.1                    py36_0    anaconda

python                    3.6.15          h39d44d4_0_cpython    conda-forge

python-dateutil           2.8.2              pyhd8ed1ab_0    conda-forge

python-json-logger        2.0.2                    pypi_0    pypi

python_abi                3.6                     2_cp36m    conda-forge

pytz                      2021.3             pyhd8ed1ab_0    conda-forge

pywin32                   301              py36h68aa20f_0    conda-forge

pywinpty                  1.1.4            py36hcae0e51_0    conda-forge

pyyaml                    5.4.1            py36h68aa20f_1    conda-forge

pyzmq                     22.3.0           py36h1d5d788_0    conda-forge

qt                        5.12.9               h5909a2a_4    conda-forge

qtconsole                 5.2.1              pyhd8ed1ab_0    conda-forge

qtpy                      1.11.3             pyhd8ed1ab_0    conda-forge

requests                  2.24.0                     py_0    anaconda

requests-oauthlib         1.3.0                      py_0    anaconda

rsa                       4.6                        py_0    anaconda

ruamel-yaml               0.17.17                  pypi_0    pypi

ruamel-yaml-clib          0.2.6                    pypi_0    pypi

scikit-learn              0.24.2           py36h5a2dbc3_1    conda-forge

scipy                     1.5.3            py36h27d303f_1    conda-forge

send2trash                1.8.0              pyhd8ed1ab_0    conda-forge

setuptools                58.0.4           py36ha15d459_2    conda-forge

six                       1.15.0                     py_0    anaconda

sqlalchemy                1.4.27                   pypi_0    pypi

sqlite                    3.37.0               h8ffe710_0    conda-forge

tbb                       2021.4.0             h2d74725_1    conda-forge

tensorboard               2.2.1              pyh532a8cf_0    anaconda

tensorboard-plugin-wit    1.6.0                      py_0    anaconda

tensorflow                2.1.0           gpu_py36h3346743_0    anaconda

tensorflow-base           2.1.0           gpu_py36h55f5790_0    anaconda

tensorflow-estimator      2.1.0              pyhd54b08b_0

tensorflow-gpu            2.1.0                h0d30ee6_0    anaconda

termcolor                 1.1.0                    py36_1    anaconda

terminado                 0.12.1           py36ha15d459_0    conda-forge

testpath                  0.5.0              pyhd8ed1ab_0    conda-forge

theano                    1.0.5            py36he2d232f_1    conda-forge

threadpoolctl             3.0.0              pyh8a188c0_0    conda-forge

tk                        8.6.11               h8ffe710_1    conda-forge

tornado                   6.1              py36h68aa20f_1    conda-forge

traitlets                 4.3.3              pyhd8ed1ab_2    conda-forge

typing_extensions         3.7.4.3                    py_0    anaconda

ucrt                      10.0.20348.0         h57928b3_0    conda-forge

urllib3                   1.25.11                    py_0    anaconda

vc                        14.2                 hb210afc_5    conda-forge

vs2015_runtime            14.29.30037          h902a5da_5    conda-forge

vs2017_win-64             19.16.27038          h2e3bad8_2    conda-forge

vswhere                   2.8.4                h57928b3_0    conda-forge

wcwidth                   0.2.5              pyh9f0ad1d_2    conda-forge

webencodings              0.5.1                      py_1    conda-forge

werkzeug                  0.14.1                   py36_0    anaconda

wheel                     0.37.0             pyhd8ed1ab_1    conda-forge

widgetsnbextension        3.5.1              pyh9f0ad1d_3    conda-forge

win_inet_pton             1.1.0                    py36_0    anaconda

winpty                    0.4.3                         4    conda-forge

wrapt                     1.12.1           py36he774522_1    anaconda

xz                        5.2.5                h62dcd97_1    conda-forge

yaml                      0.2.5                he774522_0    conda-forge

yarl                      1.6.2            py36he774522_0    anaconda

zeromq                    4.3.4                h0e60522_1    conda-forge

zipp                      3.3.1                      py_0    anaconda

zlib                      1.2.11           vc14h1cdd9ab_1  [vc14]  anaconda

zstd                      1.5.0                h6255e5f_0    conda-forge

