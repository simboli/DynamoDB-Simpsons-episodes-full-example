# Full example of DynamoDB - Python - boto3: the Simpsons episodes

![Homer VS Bill Gates](https://github.com/simboli/DynamoDB-Simpsons-episodes-full-example/raw/main/00.Media/Homer.jpeg)

## List of workbooks
001. [Get RAW data](https://github.com/simboli/DynamoDB-Simpsons-episodes-full-example/blob/main/001.%20Get%20raw%20data.ipynb)
002. [Transformations on RAW data](https://github.com/simboli/DynamoDB-Simpsons-episodes-full-example/blob/main/002.%20Transformations%20on%20RAW%20data.ipynb)
003. [DynamoDB create and populate table](https://github.com/simboli/DynamoDB-Simpsons-episodes-full-example/blob/main/003.%20DynamoDB%20create%20and%20populate%20table.ipynb)
004. [Read data from DynamoDB table](https://github.com/simboli/DynamoDB-Simpsons-episodes-full-example/blob/main/004.%20Read%20data%20from%20DynamoDB%20table.ipynb)
005. [Insert, update and delete data from DynamoDB table](https://github.com/simboli/DynamoDB-Simpsons-episodes-full-example/blob/main/005.%20Insert%2C%20update%20and%20delete%20data%20from%20DynamoDB%20table.ipynb)
006. [Drop table in DynamoDB](https://github.com/simboli/DynamoDB-Simpsons-episodes-full-example/blob/main/006.%20Drop%20table%20in%20DynamoDB.ipynb)


#### Create a credentials file
Open your favorite text editor and make a YAML file named credentials.yml like the following:

    dynamodb:
        AWS_SERVER_PUBLIC_KEY: xxxxxxxxx
        AWS_SERVER_SECRET_KEY: xxxxxxxxx
        REGION_NAME: us-east-1
