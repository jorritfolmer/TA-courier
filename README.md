# TA-courier for Splunk

This CIM compliant TA can be used with Splunk (Enterprise Security) and provides
field extractions, aliases, eventtypes and tags for courier IMAP and POP logging.

It extracts fields and maps to the following Splunk CIM datamodels:

- Authentication

## Installation

Install this TA on your Splunk (Enterprise Security) search head. Make sure to
name it TA-courier otherwise ES won't eat it. 

## Configuration

This TA expects courier logging to be sourcetyped `courier`. 

