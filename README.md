# README

This is a fullstack example of a Rails 7 application this includes 4 parts:
- Admin Web Application: Simple CRUD with Hotwire Turbo and Stimulus.
- API: Simple API with Devise-JWT authentication. and jsonapi-serializer
- FE: Simple application with NextJs and TailwindCSS
- Infrastructure: Terraform and Docker script to deploy the application to AWS ECS.

# Setup
Init new rails application with the following command:
```bash
 rails new rails-7-fullstack --skip-test --skip-action-mailer --skip-action-mailbox --database=postgresql --javascript=esbuild --css=tailwind
 ```
