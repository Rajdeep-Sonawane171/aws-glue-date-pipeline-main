To create zip file for aws lambda function 

use below commadn

```commandline
pip install --platform manylinux2014_x86_64 --target=<folder_name> --implementation cp --python 3.9 --only-binary=:all: --upgrade <lib1> <lib2>
```

```
pip install --platform manylinux2014_x86_64 --target=lambda_function_code --implementation cp --python 3.9 --only-binary=:all: --upgrade pymongo[srv] requests boto3
```
![4](https://github.com/Rajdeep-Sonawane171/aws-glue-date-pipeline-main/assets/113442602/eb53e4b4-98a0-4aee-98ab-05166e4a8229)
