<link rel='stylesheet' href='../assets/css/main.css'/>

[<< back to main index](../README.md) 

# Lab 2.1 : Up and Running With Tensorflow

### Overview
We will be running Tensorflow in a single node mode.

### Depends On 
None

### Run time
20 mins

## STEP 0: To Instructor
Please go through this lab on 'screen' first.

## STEP 1: Login to your Tensorflow node
Instructor will provide details

## STEP 2: Preparing Install

On linux, you will need to insure that the proper development libraries
are installed.


```bash
   $ sudo apt-get install python-dev python3-dev  #Ubuntu/Debian
```

```bash
   $ sudo apt-get install python-devel python3-devel  #Redhat/Centos
```


## STEP 3: Installing Tensorflow

Option 1: Installing with Pip

```bash
    $   pip3 install tensorflow
```

Option 2: Installing with Anaconda (if you have anaoconda)
```bash
    $   conda install tensorflow --ignore-installed --upgrade  <URL>
```

The URL here is as follows:
 * Mac: https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.1.0-py3-none-any.whl
 * Windows: https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.1.0-cp35-cp35m-win_amd64.whl 
 * Linux: https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-1.1.0-cp35-cp35m-linux_x86_64.whl


There is no 'install'.  Just unzip/untar and run :-)
(copy paste the following commands on terminal,  do not include $ in your commands)

```bash
    $   cd
    $   rm -rf  tensorflow   # cleanup existing tensorflow installation (if any)
    $   tar xvf   files/tensorflow-2.1.0-bin-hadoop2.7.tgz
    $   mv  tensorflow-2.1.0-bin-hadoop2.7    tensorflow
```

Now we have tensorflow installed in  `~/tensorflow`  directory


## STEP 4: Testing Tensorflow


Enter this program in your python

```python
   >>> import tensorflow as tf
   >>> hello = tf.constant('Hello, TensorFlow!')
   >>> sess = tf.Session()
   >>> print(sess.run(hello))
```

You should get the following output
```console
   Hello, TensorFlow!
```

bingo!  Now we have tensorflow running.


## STEP 5: Download Tensorflow labs
```bash
    $   cd
    $   git clone   git@github.com:elephantscale/tensorflow-labs.git

    # $  cd  ~/tensorflow-labs
    # $  git checkout master

```

This will create a `tensorflow-labs` directory that has all the labs.

