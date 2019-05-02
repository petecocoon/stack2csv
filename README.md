# stack2csv
Collect all resources information from your AWS Cloudformation Stacks into a CSV report


#Usage
./stack2csv <output-filename> <stack-filter>

For example if you want to save on resources.csv all the resource of stacks with name that starts with "my-cool-project" you have to use:

./stack2csv resources.csv my-cool-project

#AWS Environments Variables
All AWS environments variable are available, for example if you want to use a specific profile::

AWS_PROFILE=my-customer-profile ./stack2csv resources.csv my-cool-project
