
CI Pipeline
* Pull latest changes
* Run acceptance tests
* Create deployment package
* Deployment
    * Upload source to destination
    * Create new virtualenv
* Bump version via tag
    * git tag -a v1.1.2 -m 'bump minor version'
    * git commit release
* Run deployment