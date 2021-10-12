# Python Developer Task
Python task for Python Developer role applicants

## The Mission (Should you choose to accept it!)

The task is hopefully not too difficult but will involve you in some of the key tasks involved in hiring automation development:

- Send a GET request to the endpoint provided below
- Work with the response to find two Base64 encoded strings representing job descriptions
- Decode and analyse these strings
- Parse both job descriptions to find the twelve skills provided in the skills.txt file
- Output the results/frequency of your findings into any format you wish (database, csv, text)

## The Endpoint

You can make a request to the following endpoint to grab the job descriptions. No authentication is required, just specify the header content type as application/json ...

http://ciivsoft.getsandbox.com/jobs

## The Skills

You will find a text file in this repo called skills.txt containing twelve skills we would like you to look for.

## Bonus Points

It would be great if you could really show off and process the job descriptions in parallel on multiple cores, using Python's multiprocessing library.

## And Finally...

Please feel free to use any Python libraries, databases, programming methods etc you feel best showcase your skills.

If possible, please upload your solution and output data to a public git repository, and email the details over to info@ciivhub.com so we can take a look.

Thanks in advance and happy coding :)