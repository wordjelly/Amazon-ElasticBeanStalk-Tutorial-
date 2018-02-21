# Amazon-ElasticBeanStalk-Tutorial-
How to Set Up Amazon ElasticbeanStalk on Ubuntu

## Install Pip

Install anaconda for python

Not clear how to install pip thereafter, but for the purpose of elastic bean stalk, python and pip are necessary

## Install Elatic Bean Stalk Client

If eb is not already installed

```
pip install awsebcli
```

Then do

```
pip install --upgrade awsebcli
```

Now from the command line run :

```
eb --version
```

It should return the version of the eb client


### Creating an App and Environment

Go the amazon console online.

THere go to ElasticBeanStalk and Create an App.

Inside the App follow the wizard to create an environment.

Now from the console in your terminal , type

```
eb init
```

Use the same app name, and environment name that you made in the online console.

### Creating Users and Groups

Create A user, and place it inside a group.

Use this user for everything.


### Creating An ElasticSearch Cluster

Go to the elasticsearch service in the online console.

Follow the wizard to create a cluster.

Set the policy so that the user created above can be the only one to access that cluster.


### Creating A Redis Cluster



