# e2e-tests
Singular repo to deal with E2E tests for the skribble platform

----

This repo will be used to hold the e2e tests so they can be run separately from the deployment system for wave. These should be run regularly to ensure the system is working as expected.

### What is intended by this PR:

- create tests that can provide an informative output to use in a monitoring dashboard
- allow contributors outside of front-end team to contribute to and maintain tests
- add tests from a client API perspective
- improve design of wave-side tests


### The initial setup will involve:

- define user flows to be tested to be sure they are tested by this repo
- migrating tests from wave to this repo
  - this will require some changes to tests as recent wave updates have left many tests not working
- output data to integrate with a monitoring dashboard
- set up automated system and dashboard to regularly run these tests
- add tests for API to cover user flows
