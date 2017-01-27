# itemsense-postman
> A collection of ItemSense 2016r4 API calls written for usage with Postman

## Prerequisites
- Postman must be installed. For information on how to get started with Postman, please visit https://www.getpostman.com/docs/
- An ItemSense 2016r4 installation

## Install/Import
In Postman, click **Import** and either upload the file *ItemSense.postman_collection*, or provide it the direct url to the file within github. 

![Import Demo](http://g.recordit.co/d0VM4WgYKX.gif)


## Configuration
The collection uses a few default values that are configured as environment variables:

- BASE_URL : This is the hostname or IP address of your ItemSense 2016r4 instance.
- Authorization: This is setup in the request headers. Currently it is configured with the out of the box admin account for ItemSense. If the authorization is updated, make sure to click **Save**, so that it overwrites the existing stored value.
- Content-Type: set this to application/json for PUT and POST requests

### BASE_URL Update: 

![Configuration Demo](http://g.recordit.co/ACJjlphSZA.gif)

### Authorization Credentials Update

![Authorization Update](http://g.recordit.co/6niqoinDtF.gif)

## Usage
Once the default parameters are configured, navigate to a specific API call and click send! 

![Send Request Example](http://g.recordit.co/0ga3MG4r4G.gif)
