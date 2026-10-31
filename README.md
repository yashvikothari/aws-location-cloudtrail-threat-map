#  GeoGuard SecOps: AWS Impossible Travel & CloudTrail Threat Visualizer
<img width="1920" height="1023" alt="image" src="https://github.com/user-attachments/assets/df279759-b2e3-4c6b-99bf-9702eae3946e" />


An interactive geospatial security dashboard built for the AWS Location Service Challenge. It transforms raw AWS CloudTrail IAM authentication logs and threat intelligence feeds into explorable geographic attack paths and real-time velocity calculations.

##  Architecture & AWS Services Used
- **Amazon Location Service Maps v2 & Places v2:** Renders the dark vector map and reverse-geocodes verified login localities.
- **Amazon S3:** Serves as the serverless data lake storing both static web assets and threat intelligence JSON datasets.
- **Amazon CloudFront (with OAC):** Delivers the web application securely and globally over HTTPS.

##  How to Run Locally
1. Clone this repository.
2. Create an Amazon Location Service API Key with `GetTile` and `ReverseGeocode` permissions.
3. Insert your API Key and AWS Region into `index.html`.
4. Open `index.html` in your browser or serve via a local static server.

<img width="1920" height="1022" alt="image" src="https://github.com/user-attachments/assets/18077272-a7c0-4f0d-b065-7cda74562ece" />
