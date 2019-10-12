===============================================================================
README.txt
===============================================================================

Files that are part of software:
    - LiveAudioClassification.py      -> application wrapper that gets live data from user audio
    - ConversationIntentAnalysis.py   -> trained model that classifes textual data
    - MyTrainTestSplit.py             -> supplemental function that is used in the intent analyzer model above
    - data.csv                        -> contains all data samples for training model

NAME
    LiveAudioClassification.py - runs audio analysis and classification program

SYNOPSIS
    LiveAudioClassification.py

DESCRIPTION
    Exit status:
    - 0     -> if program terminated properly
    - 1     -> if input format is invalid
    - 2     -> if audio listening loop is voice-terminated
    - 3     -> if user terminates using keyboard interrupt (ie. ctrl+c)
    - 4     -> if the program terminates by choosing an invalid audio input device
    - 5     -> if program closes due to any unforseen exception

    !!! Important !!!
    Use of a Python virtual environment is highly recommended to manage all module dependencies (ie. Anaconda)
    All Python modules and Python itself that need to be installed in order for program to work:

    # Name                    Version                   Build  Channel
    _tflow_1100_select        0.0.3                       mkl
    absl-py                   0.4.0            py35h28b3542_0
    astor                     0.7.1                    py35_0
    astroid                   2.0.4                    py35_0
    backports                 1.0                        py_2    conda-forge
    backports.weakref         1.0rc1                   py35_1    conda-forge
    blas                      1.0                         mkl
    bleach                    1.5.0                    py35_0    conda-forge
    certifi                   2018.8.24                py35_1    anaconda
    colorama                  0.3.9            py35h32a752f_0
    gast                      0.2.0                    py35_0
    grpcio                    1.12.1           py35h1a1b453_0
    html5lib                  0.9999999                py35_0    conda-forge
    icc_rt                    2017.0.4             h97af966_0
    intel-openmp              2018.0.3                      0
    isort                     4.3.4                    py35_0
    lazy-object-proxy         1.3.1            py35hfa6e2cd_2
    libmklml                  2018.0.3                      0
    libprotobuf               3.5.2                    vc14_0  [vc14]  conda-forge
    markdown                  2.6.11                   py35_0
    mccabe                    0.6.1                    py35_1
    mkl                       2018.0.3                      1
    mkl_fft                   1.0.4            py35h1e22a9b_1
    mkl_random                1.0.1            py35h77b88f5_1
    mock                      2.0.0                    py35_0    conda-forge
    nltk                      3.3.0                    py35_0    anaconda
    numpy                     1.15.1           py35ha559c80_0
    numpy-base                1.15.1           py35h8128ebf_0
    pbr                       4.2.0                      py_0    conda-forge
    pip                       10.0.1                   py35_0
    portaudio                 19.6.0               hfa6e2cd_3    anaconda
    protobuf                  3.5.2               py35_vc14_0  [vc14]  conda-forge
    pyaudio                   0.2.11           py35hfa6e2cd_1    anaconda
    pylint                    2.1.1                    py35_0
    python                    3.5.6                he025d50_0
    scikit-learn              0.19.1           py35hae9bb9f_0
    scipy                     1.1.0            py35h4f6bf74_1
    setuptools                40.2.0                   py35_0
    six                       1.11.0                   py35_1
    speechrecognition         3.6.3                    py35_0    conda-forge
    tensorboard               1.10.0           py35he025d50_0
    tensorflow                1.3.0                    py35_0    conda-forge
    tensorflow-base           1.9.0           eigen_py35h45df0d8_0
    termcolor                 1.1.0                    py35_1
    typed-ast                 1.1.0            py35hfa6e2cd_0
    vc                        14                   h0510ff6_3
    vs2015_runtime            14.0.25123                    3
    webencodings              0.5.1                      py_1    conda-forge
    werkzeug                  0.14.1                   py35_0
    wheel                     0.31.1                   py35_0
    wincertstore              0.2              py35hfebbdb8_0
    wrapt                     1.10.11          py35hfa6e2cd_2
    zlib                      1.2.11                   vc14_0  [vc14]  conda-forge