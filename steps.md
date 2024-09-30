Cloud Formation
Create EC2 from cloud formation:

1.	Create a json file on notepad with the properties as mentioned and any other properties mentioned in the question, 
use online json editor for identation.
2.	AWSTemplateFormatVersion : '2010-09-09'
Resources:
(tab) EC2Instance:
 (tab) Type: AWS::EC2::Instance
 (tab)Properties:
  (tab)InstanceType: t2.micro
  (tab)ImageId: ami-0182f373e66f89c85 # to is get this ami id go on instances , click launch instance in quick start browse for more instances 
   you will get the info of the ami linux machine , ensure that it uefi preffered  
3.	Save this file with .json extension
4.	Search Cloud formation in search bar 
5.	Create stack 
6.	Choose an existing file if template is provided in the question or create a json file  whatever the question provides.
7.	Upload the file (json file )
8.	Next
9.	Stack name > ecstack1
10.	next
11.	stack will get successfully created , go on instances and check if the instance is running.
