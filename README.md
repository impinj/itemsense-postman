# itemsense-postman
> A collection of ItemSense's API calls written for usage with Postman

## Prerequisites
In order to use this, Postman must be installed. For information on how to get started with Postman, please visit https://www.getpostman.com/docs/

## Install/Import
In Postman, click **Import** and either upload the file *ItemSense.json.postman_collection*, or provide it the direct url to the file within github. 

## Configuration
The collection uses a few default values that are configured as environment variables:

- BASE_URL : This is the hostname where your itemsense instance lives.
- Authorization: This is setup in the request headers. Currently it is configured with the out of the box admin account for ItemSense. If the authorization is updated, maked sure to click **Save**, so that it overwrites the existing stored value.

## Usage
Once the default parameters are configured, navigate to a specific API call and click send! 
