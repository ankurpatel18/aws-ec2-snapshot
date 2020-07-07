# AWS EC2 snapshot
EC2 snapshot with python


## About
 This project is using boto3 to manage EC2 snapshot

## Configuring

Configure AWS CLI profile with 'shotty' name

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command> <subcommand> <--Project=PROJECT>`

*command* is instances, volumes or snapshots

*subcommand* depends on the command

*project* is optional