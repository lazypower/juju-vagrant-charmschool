# Testing

Clone the `Vagrantfile` and `vagrant-test-runner.sh` to the root of your charm. From there the Vagrantfile and vagrant-test-runner.sh will take care of:

- Setting up the machine with Juju
- Executing any tests you have in the tests/ directory that are chmod +x

to re-execute after the initial run (to save time with provisioning) run

`vagrant provision`
