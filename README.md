# aws-dynamodb-python-lab
Simple AWS DynamoDB CRUD exercise using Python and boto3


# DynamoDB CRUD Practice with Python
This project is a small exercise using Python (boto3) to interact with an AWS DynamoDB table.

## What the script does
- Adds a new item to a DynamoDB table using `put_item`
- Retrieves the same item using `get_item`
- Prints the result to confirm the operation worked

## Technologies Used
- Python
- boto3
- AWS DynamoDB


### 🔧 What I built
Inside the `dynamodb.py` file, I:

- Inserted a new item into a DynamoDB table (`LanguagesTable`)
- Retrieved that item using its primary key (`Code`)
- Printed the output to verify the CRUD operations worked


## 🧠 What I learned
- How DynamoDB stores attributes using types (e.g., `"S"` for string)
- How to work with `put_item` and `get_item` using boto3
- Running AWS CLI commands with output formatting (awk + JMESPath)
- Why verifying resources before coding is essential in cloud environments

