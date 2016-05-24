# geolocation_api
API for Resolving Street Address and Geolocation Information

Run the Python script 'python geolocation_api.py' to launch the API. The default port is 5000. The port is configurable in the main params.

The primary API endpoint is /street-address.

A demo query is:
GET /street-address?street=1600+pennsylvania+ave,+washington,+dc,+20500

which returns structured JSON data about the resolved address, as well as latitude and longitude information from the Google maps API.