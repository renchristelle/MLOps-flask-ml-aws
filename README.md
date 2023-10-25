# MLOps Flask Application on AWS Elastic Beanstalk with AWS Pipeline
This is a repo for deploying a Flask Machine Learning Application on AWS Elastic Beanstalk with AWS Pipeline


This project is built with python3.9.



## To run it locally follow these steps (on Python 3.9)

1.  Create and source your virtual environment. Install the required packages

```bash
python3 -m venv ~/.flask-ml-aws
source ~/.flask-ml-aws/bin/activate
pip install -r requirements.txt
```

2.  Run application: `python application.py`
   

## To run it in [AWS](http://mlops-flask-ml-aws-env.eba-7dfmqgrz.eu-north-1.elasticbeanstalk.com/) 

### Deploy the application with [Elastic Beanstalk](https://eu-north-1.console.aws.amazon.com/elasticbeanstalk/home?region=eu-north-1#/environments) 

Create an application and an environment (Refer to [AWS Official Documentation](https://docs.aws.amazon.com/fr_fr/elasticbeanstalk/latest/dg/GettingStarted.CreateApp.html)).


### Deploy with [AWS CodePipeline](https://eu-north-1.console.aws.amazon.com/codesuite/codepipeline/pipelines?region=eu-north-1&pipelines-meta=eyJmIjp7InRleHQiOiIifSwicyI6eyJwcm9wZXJ0eSI6InVwZGF0ZWQiLCJkaXJlY3Rpb24iOi0xfSwibiI6MTAsImkiOjB9)

Create a AWS Pipeline sourcing from Github and deploying to the Elastic Beanstalk environment.


<!-- 
Ressources:
https://www.youtube.com/watch?v=m1mWjC1VFY4&ab_channel=AWSUserGroupIndia
https://www.red-gate.com/simple-talk/blogs/deploying-a-nodejs-application-from-github-to-aws-elastic-beanstalk-and-creating-a-ci-cd-aws-codepipeline/
-->
