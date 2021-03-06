# Formica Documentation

1. Commands reference
  * [change:](commands/change.md) Create a change set for an existing stack
  * [deploy:](commands/deploy.md) Deploy the latest change set for a stack
  * [describe:](commands/describe.md) Describe the latest change set
  * [diff](commands/diff.md) Print a diff between local and deployed stack
  * [new:](commands/new.md) Create a change set for a new stack
  * [remove:](commands/remove.md) Remove the configured stack
  * [resources:](commands/resources.md) List all resources of a stack
  * [stacks:](commands/stacks.md) List all stacks
  * [template:](commands/template.md) Print the current template
2. [Template files reference](template-files.md)
3. [Config files](config-files.md)
3. [Module System](modules.md)


## Examples

# Module System
* [nested and relative modules](examples/nested_relative_module)

# S3
* [Simple S3 Bucket](examples/s3-bucket)
* [S3 Bucket that runs Lambda on File upload/remove](examples/s3-lambda)

# Step Functions
* [Lambda Step functions with dynamic steps](examples/lambda-step-function)

# Custom Resources
* [Custom Resource](examples/custom-resource)

# CodeCommit, CodePipeline, CodeBuild

 * [CodeCommit and CodeBuild for every push](examples/commit-build)
 * [CodeCommit -> CodePipeline -> CodeBuild for the master branch](examples/commit-build-pipeline)

# Configuration File

 * [Configuration File](examples/config-file)