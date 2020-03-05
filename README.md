# dokerized_training_environment
A training environment, with docker.

nginx is a reverse proxy allowing you to conect to all the MISPs instance:
* http://misp-central.local
* http://misp-1.local
* ....

# What does what

* `init_misps.py`: Initialize N dockers
* `stop_misps.py`: Guess.
* `refresh_misps.py`: Run the refresh script on all the MISP instances
* `setup_sync.py`: Setup sync from nodes to central
* `setup_nginx.py`: Setup nginx
* `start_nginx.py`: Start nginx
* `stop_nginx.py`: Stop nginx
