# Rails Ansible


### About

Most of the code is taken from https://github.com/cupnoodle/rails-ansible which proved to be a 85% working solution, but it failed on several places, possibly due to newer OS version.

Note: This Ansible script is for Ubuntu 22.04 LTS server.
This Ansible script will setup a server with the following components

1. Ruby
2. Nginx web server
3. Passenger app server
4. PostgreSQL
5. Sidekiq

### How to
Make sure to copy all smaple files e.g. hosts.sample.ini, vars.sample.yml and envs.sample.yml to their non sample versions and replace all containing app specific values with the values of your application.

For sidekiq, When setting up your deployment make sure to use the same commands as stated in sidekiq.service.j2
