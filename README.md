# testspace.test.specs
Collection of Test Specs used for testing

## Concurreny 
The **concurrency** branch is based off the `main` branch minus:

- `.github\workflows` - different GitHub workflows for testing 
- `fixtures` - contains the aws test fixture
- `specs\fixtures.aws` - specs for aws, including errors
- `specs\fixtures.github` - specs for github, including errors

The above folders are removed to reduce noise and are not used for the system concurrency tests. 