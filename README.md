
# Maybe* 

Maybe* is a social media management platform which gives businesses:

A way to compare your social media performance with any other business.

All the social media tools and insights you need to get more from social media.

Access to expert resources and training to help you reach more customers.

## Getting Started

 Follow the below instructions on setting up your project locally. To get a local copy up and running follow these steps.

 ### Prerequisites

 Install the below applications.

- LAMP [MySql - 5.7, PHP - 7.1]
- Node - V12
- Composer - V1.10
- PhpMyAdmin
- Git
- Virtual Host for MFB & MSA
- Redis
- Supervisor
- SSL
- WorkBench
- Insomnia / Postman
- VSCode / Sublime Editor

### Installation

Follow the below steps for setting up the project.

- git clone https://github.com/maybeapp/maybe-business.git Provide username and password for the same

- Run composer install
- Run cp .env.example .env or copy .env.example .env
- Run php artisan key:generate
- Run php artisan migrate
- Run php artisan db:seed
- Run npm install && npm run dev

#### Execute the following git commands.

````
master switch to dev
git checkout dev
git fetch origin dev
pull- git pull origin dev
git checkout -b feature-branch-name dev
git add filename1 filename2
git commit -m "change"
git push origin feature-branch-name
git checkout dev
git merge  feature-branch-name
````
## Acknowledgements

 - [About Maybe*](https://www.maybetech.com/about/)
 - [Guides info](https://www.maybetech.com/guides)
 - [Pricing](https://www.maybetech.com/pricing/)

