# SageMakerStudio-Sept-2025

# Lab is updated! The error in a task on the capstone lab is sorted. Class was updated to the latest version on Sep 12th, at 8:00 AM US Eastern
## Class evaluation
- Go to [aws.training](https://www.aws.training/)
- Click sign in, log in with the same account you used to access the lab and course materials
- Then go on the top right to My Account, then transcript, click on the Archived section (direct link [https://www.aws.training/Account/Transcript/Archived](https://www.aws.training/Account/Transcript/Archived)
- You should see the class, with a button to evaluate

## Contact details
- email: renatoalmeidamartins@gmail.com
- [Linkedin profile](https://www.linkedin.com/in/renatodealmeidamartins/)
  
## Class links

- [Access to lab environment](https://us-east-1.student.classrooms.aws.training/class/ilt%23v8Tx76fddYa18jg1vJvvjX)
- [List of available courses](https://releases.awstc.com/)

### Day 1 links
- [Build and deploy a scalable machine learning system on Kubernetes with Kubeflow on AWS](https://aws.amazon.com/blogs/machine-learning/build-and-deploy-a-scalable-machine-learning-system-on-kubernetes-with-kubeflow-on-aws/)
- [AWS technical essentials on Skill builder](https://skillbuilder.aws/learn/K8C2FNZM6X/aws-technical-essentials/N7Q3SXQCDY)
- [Sagemaker studio lab](https://studiolab.sagemaker.aws/login)
- [Sagemaker studio lab documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-lab.html)
- [Using multiple domains](https://docs.aws.amazon.com/sagemaker/latest/dg/domain-multiple.html)
- [Useful Jupyterlab extensions](https://towardsdatascience.com/10-jupyter-lab-extensions-to-boost-your-productivity-4b3800b7ca2a/)
- [Migrating from sagemaker classic to "new" studio](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-updated-migrate.html)
- [Options for customizing JupyterLab environment](https://docs.aws.amazon.com/whitepapers/latest/sagemaker-studio-admin-best-practices/customization.html)
- [Sharing models and notebooks, also using Sagemaker JumpStart](https://aws.amazon.com/blogs/aws/new-share-ml-models-and-notebooks-more-easily-within-your-organization-with-amazon-sagemaker-jumpstart/)
- [EMR releases](https://docs.aws.amazon.com/emr/latest/ReleaseGuide/emr-release-components.html)
- [Connecting EMR serverless to Sagemaker](https://docs.aws.amazon.com/next-generation-sagemaker/latest/userguide/emr-serverless.html)
- [List of PySpark magic commands in Glue Interactive sessions](https://docs.aws.amazon.com/glue/latest/dg/interactive-sessions-magics.html)
- [Some additional PySpark magic commands](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-studio-magics.html#accessing-all-magic-commands)
- [Using Glue Interactive sessions, required images and kernels](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-notebooks-glue.html)
- [Sagemaker Python SDK](https://sagemaker.readthedocs.io/en/stable/)
- [Possible ordinal encoding used, inferring order based on mean values for the target variable](https://feature-engine.trainindata.com/en/1.8.x/user_guide/encoding/OrdinalEncoder.html#ordered-ordinal-encoding) . Important to note that this info is not there in the docs for scikit or sagemaker, but based on the outcome of Data Wrangler seems to be what is used:
  - [Data wrangler](https://sagemaker-examples.readthedocs.io/en/latest/sagemaker-datawrangler/tabular-dataflow/data-transformations/index.html#handle-categorical-data)
  - [Scikit](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OrdinalEncoder.html)
- [Job Function policies - permissions that](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_job-functions.html)

## Day 2 links
- [Time series transformations in Data Wrangler](https://docs.aws.amazon.com/sagemaker/latest/dg/data-wrangler-transform.html#data-wrangler-transform-time-series)
- [Sagemaker built-in algorithms](https://docs.aws.amazon.com/sagemaker/latest/dg/algos.html)
- [Deep learning images availabel in Sagemaker](https://docs.aws.amazon.com/sagemaker/latest/dg/pre-built-containers-frameworks-deep-learning.html)
- [Sagemaker Spark SDK](https://github.com/aws/sagemaker-spark)
- [Custom Docker containers with Sagemaker AI](https://docs.aws.amazon.com/sagemaker/latest/dg/docker-containers-adapt-your-own.html)
- [Sagemaker debugger rules](https://docs.aws.amazon.com/sagemaker/latest/dg/use-debugger-built-in-profiler-rules.html)
- [HyperParameterTuner documentation](https://sagemaker.readthedocs.io/en/stable/api/training/tuner.html)
- [AWS Artifact, place to obtain compliance reports about AWS services and data centers](https://aws.amazon.com/artifact/)
- [AWS config conformance packs](https://docs.aws.amazon.com/config/latest/developerguide/conformancepack-sample-templates.html)
- [MLFlow from inside Sagemaker Studio](https://docs.aws.amazon.com/sagemaker/latest/dg/mlflow.html)
- [Sagemaker Clarify SDK operations run_xxxx](https://sagemaker.readthedocs.io/en/stable/api/training/processing.html#sagemaker.clarify.SageMakerClarifyProcessor)
- [Sagemaker training toolkit](https://github.com/aws/sagemaker-training-toolkit)
- [Using spot instances on sagemaker](https://docs.aws.amazon.com/sagemaker/latest/dg/model-managed-spot-training.html)
- [Spot instance advisor](https://aws.amazon.com/ec2/spot/instance-advisor/)
- [Sagemaker registry model cards](https://docs.aws.amazon.com/sagemaker/latest/dg/model-cards.html#model-cards-json-schema)
- [Defining a Sagemaker Pipeline using Python code](https://docs.aws.amazon.com/sagemaker/latest/dg/define-pipeline.html)
- [Sagemaker Pipeline step types](https://docs.aws.amazon.com/sagemaker/latest/dg/build-and-manage-steps-types.html)
- [Sagemaker inference recommender](https://docs.aws.amazon.com/sagemaker/latest/dg/inference-recommender.html)

## Day 3 links
- [Model Monitor sample notebooks](https://github.com/aws-samples/amazon-sagemaker-model-monitor-using-bring-your-own-model/tree/main)
- [Sagemaker studio auto shutdown available since September 2024, without needing an extension](https://aws.amazon.com/about-aws/whats-new/2024/09/amazon-sagemaker-studio-automatic-shutdown-idle-applications/)
- [For reference, the auto shutdown extension](https://github.com/aws-samples/sagemaker-studio-auto-shutdown-extension)
- 
