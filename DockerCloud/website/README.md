# IoT-Cloud-Testbed Dashboard
Visualizes probability of rain, latest sensor data and provides report logging.

## Features
- Responsive mobile-friendly design


## Test and Run
### Locally (without Docker)
1) Simply start the script 'webservice.py':

        $ python webservice.py 8080

2) Navigate to http://localhost:8080/

3) Change 'API url' field to 'mockup_sensor_values.json'

### Docker
1) Start docker by executing:

        $ sudo docker-compose up
2) Navigate to http://localhost
