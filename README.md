# jira-software-docker-compose

This is a small and simple docker compose file for jira software. Before using it, adjust the mysql envoriment on docker/dockerfile-mysql.

1. `git clone`
1. `vim docker/dockerfile-mysql` and set another password
1. `docker-compose up -d`
1. follow the installation guide

# Recommendation

Use nginx as reserve proxy with and lets encrypt ssl certication
