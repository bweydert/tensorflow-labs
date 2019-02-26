# tensorflow-labs

These are labs for our Deep Learning with Tensorflow and Keras course.

## Running the Labs

There are two main ways we recoommend running the Labs:

1. Locally
2. Hosted on [Google Colaboratory](https://colab.research.google.com/)

#### Running Locally

To Run locally, we recommend downloading and installing [Anaconda](https://www.anaconda.com/distribution/#download-section)

Here is the URL for your copy-and-pasting pleasure:

`https://www.anaconda.com/distribution/#download-section`

Make certain you download Anaconda for Python version **3**, **NOT** Python version **2**.

#### Running with Google Colaboratory

[Here](./colab-intro.md) is a guide for running with Google Colaboratory.

## For instructor

### AWS option 1

Recommend running with the `deeplearning` AMI, which is a fork of Amazon's DL AMI.

Start a new EC2 Instance as follows:
  * AWS us.east region
  * p2.xlarge instance type.
  * make sure network has public IP address
  * `deeplearning` AMI
  *  `hi.pem` key
  * `ubuntu` security group.

### AWS option 2

I used instances c4.4xlarge, at $0.80/hour, or $200/day for 10 students.

For more than 5 students, you may want 
to stop them after the class and restart in the morning.

The speed that you get with these is 2 times faster than my fast Mac.

