# Zoom Video Ingester

A set of AWS services for downloading and ingesting Zoom meeting videos into Opencast

## Setup

Python 3 is required.

1. `pip install requirements_dev.txt`
1. copy `example.env` to `.env` and update as necessary

## Commands

This project uses the `invoke` python library to provide a simple task cli. Run `invoke -l`
to see a list of available commands.

The current list of commands includes:

##### `invoke create`

Build the Cloudformation stack

##### `invoke update`

Apply template changes to the stack

##### `invoke delete`

Delete the stack
