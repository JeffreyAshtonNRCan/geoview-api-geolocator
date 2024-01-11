# Cloud Formation Script

## Deployment steps

1. configure your aws cli
2. cd to the `backend` folder and run the deploy script: `./deploy.sh`

## Deployment steps with Cloud9

1. create Cloud9 instance
2. clone repo
3. cd geoview-api-geolocator
4. open command line or programmatic access on aws login page
4. copy setup AWS Short-term credentials (option 1) and paste
5. cd to the `backend` folder
6. mkdir build-artifacts
7. run the deploy script: `./deploy.sh`

## To Do

- [ ] setup CI/CD based on AWS codepipeline.
- [ ] set proper names for exported variables, bucket, etc.