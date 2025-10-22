# HTWG-Cloud-App-Dev-HW3
How to Build

<pre>
docker build -t cloud-app-hw .
</pre>
<br>
Deploy the container on Cloud Run,<br>
please deploy backend and frontend container seperately, and<br>
set port to 3000 for backend,<br>
set port to 5173 for frontend.<br><br>

Environment Variable:<br>
For the Seperated backend and frontend container,<br>
<code>VITE_API_BASE_URL</code> should fill in backend server URL<br>
such as:
<code>https://xxxxxx.asia-east1.run.app</code><br>
<code>http://x.x.x.x:3000</code><br>
For All in one container, there's nothing to do with this


# 
Create a branch of your application, where all data is stored in cloud storage and application is deployed on PaaS.
Compare elasticity of IaaS with PaaS deployment.


## Instructions

* Use PaaS to deploy application.
* Use Managed-SQL database to store data.
* Provide CLI script to deploy / delete application.
* Create load test script which tests the limits of the IaaS deployment, you may test different machine types.
* Run the same script on the PaaS deployment and compare outcome.

## User Stories

### Search Trips
As a guest or traveller I can search for itineraries of other travellers.

#### Acceptance Criteria
* I can input various search criteria
* The result is shown in a list

## Deliverables
* Update your git repository with the code changes and the deployment code
* Upload test report to moodle.
## Demo
* Demo of PaaS Deployment with scripts
* Discussion on load test results.
