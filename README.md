#snapshotalyzer-30000
Demo project to manage AWS EC2 instances snapshots

##  About

This project is a demo and uses boto3 to manage AWS EC2 instances

## Configuring

shotty uses the configuration creates by the AWS cli e.g.
`aws config --profile shotty`

## Running

`pipenv run "python shotty/shotty.py"`
*command* is list, start, or stop
