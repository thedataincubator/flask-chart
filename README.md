# flask-chart

Very simple chart for a Flask application.

This helm chart defines a deployment, service, and (optional) ingress for a Flask application.

The Flask application is assumed to be serving on port 5000, this port can be passed into the Docker run command with an environment variable.  For a sample application that would run with this chart, check out [python-miniconda](https://github.com/heroku-examples/python-miniconda).
