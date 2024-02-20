To create zip file for aws lambda function 

use below commadn

```commandline
pip install --platform manylinux2014_x86_64 --target=<folder_name> --implementation cp --python 3.9 --only-binary=:all: --upgrade <lib1> <lib2>
```

```![5](https://github.com/Rajdeep-Sonawane171/aws-glue-date-pipeline-main/assets/113442602/eeb31f60-8786-4516-9d16-2d16c0bf158b)

pip install --platform manylinux2014_x86_64 --target=lambda_function_code --implementation cp --python 3.9 --only-binary=:all: --upgrade pymongo[srv] requests boto3
```

Uploading the webapi data to s3

![4](https://github.com/Rajdeep-Sonawane171/aws-glue-date-pipeline-main/assets/113442602/eb53e4b4-98a0-4aee-98ab-05166e4a8229)

Integrating data from s3 to DynamoDB
![5](https://github.com/Rajdeep-Sonawane171/aws-glue-date-pipeline-main/assets/113442602/eeb31f60-8786-4516-9d16-2d16c0bf158b)
