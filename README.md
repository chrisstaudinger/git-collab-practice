![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/images/logo2v2.png?raw=true "Home Grown Local Logo")

# Home Grown Local

### [View Live application](https://homegrownlocal.herokuapp.com/)

#### Contributers
##### Chris
![](https://avatars1.githubusercontent.com/u/16986875?s=460&v=4 "Chris Profile Pic")
##### Suki
![](https://avatars1.githubusercontent.com/u/42060507?s=400&v=4 "Suki Profile Pic")
##### Selly
![](https://avatars2.githubusercontent.com/u/49693577?s=400&v=4 "Selly Profile Pic")

## Contents
<!-- links  -->
**[Section 1: Description](#Section-1:-Description)**

**[About](#About-Home-Grown-Local)**\
**[Tech Stack](#Tech-Stack)**\
**[Configuration](#Configuration-/-Installation-Instructions)**\
**[Screenshots](#Screenshots)**\
**[Version Note](#Version-Note)**



**[Section 2: Planning](#Section-2:-Planning-And-Project-Management)**

**[Sitemap](#Sitemap)**\
**[Idea Conception](#Idea-Conception)**\
**[Project Management](#Project-Management)**\
**[Version / Source-Control](#Version-/-Source-Control)**\



# Section 1: Description

## __About Home Grown Local__
 Home Grown Local is an open source two-sided marketplace helping to put money back into the pockets of everyday Australians rather than corporate conglomerates. The goal of the application is to bring Australian communities greater ability to buy fresh, local and organic produce, bringing people towards a healthy lifestyle. 

## Tech Stack

* Front-end: HTML, ERB, CSS, Sass, Javascript
* Back-end: Ruby, Ruby on Rails
* Database: PostgreSQL Database with ActiveRecord
* Deployment: Heroku

## Configuration / Installation Instructions

This application is running:
* Ruby v2.6.3
* Rails v5.2.3
* PSQL v11.4
* Java v12.0.1

Within your computer terminal, navigate to the directory where you want to install the application files, and run the following commands:
1. Run git clone to install the application files
``` ruby
git clone git@github.com:chrisstaudinger/home-grown-local.git
```

2. (If you haven't got homebrew installed, run the command below, otherwise skip this step and go to step 3.)
``` ruby
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
3. Install & Run Elasticsearch
```ruby
brew update
```
```ruby
install elasticsearch
```
```ruby
elasticsearch
```

3. (If you haven't got bundler installed, run the command below, otherwise skip this step and go to step 4.)

``` ruby
gem install bundler
```

4. Run 'bundle install' to install the dependencies

``` ruby
bundle install
```

5. Run rails s to run the server in development mode
``` ruby
rails s
```

6. Run 'rails db:reset' to reset the database
``` ruby
rails db:reset
```

7. In your browser, navigate to 'http://localhost:3000/' to view the website

## Screenshots

![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/readme%20screenshot%20attachments/site-screenshot/root-screenshots/whole-site-screenshot.png?raw=true "Home Grown Local Home Page")

![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/readme%20screenshot%20attachments/site-screenshot/item-showpage-screenshot/item-show-complete-screenshot.png?raw=true "Item Page")

![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/readme%20screenshot%20attachments/stripe-1.png?raw=true "Stripe Integration Image")

![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/readme%20screenshot%20attachments/watchlist-1.png?raw=true "User Watchlist Image")


![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/readme%20screenshot%20attachments/login-1.png?raw=true "Login Image")


![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/readme%20screenshot%20attachments/new-item-1.png?raw=true "Post An Ad Image")

### Version Note
Currently the version of this application is version 1.0. This application was built in the space of 3 weeks and some of the content such as the sitemap and userflow were built having future versions in mind. Therefore, some aspects of version 1.0 may differ from the resources listed in the this document.


# Section 2: Planning And Project Management

## Idea Conception

![]( "Brainstorming Idea Image")

Coming up with the idea was a very collaborative process. We all brainstormed ideas on individually for a set period of time and listed them all together. From here we individually analysed the ideas, shared our evaluations, shortlisted the best ones, re-evaluated them and reached consensus on the idea.

A lot of our initial inspiration was drawn from Airbnb and Uber; their ability to create an product/service from utilising dormant resources. Once we settled on Home Grown Local, a lot of inspiration was drawn from Gumtree.

## Project Management

### Project Spec Sheet
![]( "Project Spec Sheet")

Afrer we settled on our application idea, we created a project spec sheet. The project spec sheet was the overview compass of our application.

### Kanban Board
![]( "Kanban Board")

From the outset we utilised a kanban board through Trello. Tasks were throughly broken down, planned out and labelled to acheive our MVP, then future versions. Tasks were assigned to an individual team member to take responsibility for getting the tasks completed. Moreover, comments were used on the cards for progress or blocker updates. Cards were assigned due dates.

### Sprint Meetings & Stand Ups

With a project timeline of 3 weeks we conducted sprint meetings at the start of each week. The sprint meetings were used as a tool to ensure team members were all on the same page, and from an overview perspective we were heading in the right direction and on track. The following is what was covered in the sprint meetings:

* Evaluation of what needs to be done
* Evaluation of how we are going
* Discuss any pivoting that needs to be done or any blocker we had or may come up in the following week

Stand ups were done a on a daily basis first thing in the morning as a tool for communication between the team. The below is what was covered in the stand ups:

* Rating ourselves from 0-5 of how we are tracking for the task we set ourselves in the sprint meeting
* Stating what we acheived in the last 24 hours
* Discussing any blockers we had
* Stating what we plan to acheive in the next 24 hours


## Application Achitechture And Design

Most of the first week of the project was spent on designing the achitecture of our application.

* Database Design (ERD)
* Sitemap
* Userflow (User-journey)
* User Stories


### Database Design (ERD)

![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/Home%20Grown%20Local%20Site%20Map%20(2).png?raw=true "Database Design (ERD")

### Sitemap

![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/Home%20Grown%20Local%20Site%20Map%20(2).png?raw=true "Sitemap")

### Userflow (User-journey)

![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/Home%20Grown%20Local%20Site%20Map%20(2).png?raw=true "Userflow")

### User Stories

![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/Home%20Grown%20Local%20Site%20Map%20(2).png?raw=true "User Stories")

### Wireframes

![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/Home%20Grown%20Local%20Site%20Map%20(2).png?raw=true "User Stories")

### Mockup

![](https://github.com/chrisstaudinger/home-grown-local/blob/readme/app/assets/resources/Home%20Grown%20Local%20Site%20Map%20(2).png?raw=true "User Stories")


## Version / Source-Control

We used Git CLI, Git GUI's, GitHub and Heroku CLI for source control / version control. Each new feature was a new branch. Once was the feature was completed locally, the branch was pushed to github and a pull request was submitted for another team member to review. Once the code review was completed, if it was approved, the team member would pull origin master to the local version of that 'feature' branch and test it locally (this was done to ensure if there were any merge conflicts from other commits to master, they would should locally and testing could be done locally rather than production). If testing worked properly, the team member would merge that local feature branch to their local master and push their master branch to origin master.

Origin master was pulled at least once daily by team members to ensure build ups of merge conflicts did not occur.

Every day we would push the origin repository to a Heroku repository created on only one computer to confirm our build.


