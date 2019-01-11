# The SafeWork Project

The SafeWork Project is a sex worker support web app designed to help provide sex workers resources in an increasingly difficult and dangerous environment.

Currently located at safeworkproject.org

## Getting Started

### Prerequisites

-Running a Linux System (Developed and Tested on Ubuntu 18.04)

-System can be run on Python 3.6.5+

### Installing

-Clone/Download the repo from https://github.com/beegeiger/Safework-Project

-Create a virtual environment ($virtualenv env) and activate it ($source env/bin/activate)

-Install requirements ($pip install -r requirements.txt)

-Create psql database called "safework" ($createdb safework)

-Seed Database:

-Run server.py ($python server.py)

-The app should be running on your local system!


## Testing

Tests for the SafeWork Project can be found in tests.py. Right now, only a relatively small portion of the app is tested and adding tests is a top priority!

## Deployment

The app is currently live at safeworkproject.org and is running on an AWS lightsail server using nginx as a proxy server to only make connections through https.

## Built With

* [Flask](http://flask.pocoo.org/) - The web framework used

## Contributing

Please read [contributing.md](https://github.com/beegeiger/Safework-Project/blob/master/docs/contributing.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/beegeiger/Safework-Project/tags). 

## Authors

* **Dorothy Bee Geiger** - *Initial work* - [SafeWork Project](https://github.com/beegeiger/Safework-Project)

See also the list of [contributors](https://github.com/beegeiger/Safework-Project/blob/master/docs/contributing.md) who participated in this project.

## Acknowledgments

* Hackbright Academy for Teaching Dorothy Bee the Basics to create this app.
