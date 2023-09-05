- 👋 Hi, I’m @ryandagley
- 👀 I’m interested in building cool solutions on AWS and working with AI.
- I write a ton of SQL at work and I'm looking to expand my knowledge.
- Welcome to my codes.
- Challenging myself to Commit 100 days in a row (some code, some other exploration).
[![GitHub Streak](https://streak-stats.demolab.com/?user=ryandagley)](https://git.io/streak-stats)

Things I'm studying this week:
1. CDK
2. Headless Wordpress
   
<!---
ryandagley/ryandagley is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<details>
   <summary> <strong> Week 1: </strong> Days 1-7 of 100</summary>
   
* Day 1: Wrote an OpenAI API connector.
* Day 2: Wrote an outline for OpenAI text summarization script.  Added some SQL for writing a table with dummy data.
* Day 3: I learned to write an AWS Lambda function that checks for S3 objects older than 7 days and e-mails me a list.  I was specifically curious to learn how to use S3 objects with s3.list_objects_v2.
* Day 4: I learned to deploy Day 3's Lambda function to AWS via CDK (not pushed).  This required guidance of a seasoned engineer who taught me how to structure my applications to use environment variables.
* Day 5: Continued focus on using environment variables with a Python CDK application.  I'm also having general difficulty with my Docker installation so will continue another day without pushing changes.  I'm gathering some questions to ask my engineering mentors when I see them this week.
* Day 6: Wrote a CDK application for creating S3 buckets.  I spent some time learning about deploying with "cdk deploy" and "npx".  I'm learning to be cautious about what I commit to Github with CDK as it seems it could be fairly easy to expose resources to the public that I would not want to.
* Day 7: Thrilled that I've completed a one week streak on commits!  Today I built the start of a portfolio page for my projects using HTML, CSS, and JavaScript.  This will be the visual home for my ongoing projects.  In doing this I learned a little bit about the visual aspects of building a website to include playing a movie in the background and a button to turn music on and off.  At some point I'll want to host it on AWS and deploy using CDK (or similar).

</details>

<details>
   <summary> <strong> Week2: </strong> Days 8-14 of 100</summary>
   
* Day 8: Looking back on the past week, I'm realizing that I'm all over the place.  I think this is reflective of how things go at work.  I will benefit from planning out projects a bit more.  I've pushed a project proposal to my portfolio project to guide my next steps.
* Day 9: I just added a Github Stats widget and I'm graded with a C!  I've written some project plans for my portfolio project.
* Day 10: I'm planning the architecture for my portfolio project and leaning toward next.js.  I'm also writing some tests in python to test my SQL queries at work.
* Day 11 / Aug 25 2023: I've decided on my front and backend technologies for the portfolio site. Using next.js and tailwind, I've started to build the front-end.
* Day 12: I've learned to add a second component to my next.js front end.  It's as simple as importing the page from another folder.  Next is pleasantly easy to work with for what I'm building.
* Day 13: I've added a couple more components to the site.  I learned about creating creating grids and got in some logo design practice in Canva.
* Day 14: Two weeks already!  Today I learned to make a hovering box with a link of my Next.js site.  A small feat, but looks great!  This is also Day 7 of my project plan: https://github.com/ryandagley/portfolio_site/blob/main/docs/Project%20Plan.pdf  I'm building this a little bit different than planned as I'm concerned that I did not leave myself enough time to build some of the larger components of this project, but I am definitely ahead of schedule!  I learned a few more things like smooth-scrolling and how to create the outline of a contact form.

</details>

<details>
   <summary> <strong> Week3: </strong> Days 15-21 of 100</summary>

* Day 15: Learned to build collapse and navigate functionality on my website's mobile menu.  This is coming along well!  I had a long commute today so I watched a few tutorials on using CDK to deploy a CI/CD pipeline for S3 hosted static websites.
* Day 16: Added a page specific to my Mycologeek project in the portfolio website.  I'm quickly learning that I don't really have many projects to showcase outside of work.
* Day 17: I learned a bit more about passing variables from the CDK context throughout the app.  One instance was passing a cron dictionary.  On my website, I built some buttons and made some progress on the CDK.  I'm using Typescript which is new for me.
* Day 18:  September 1st!  And day 11 of my portfolio project plan.  I'm certain that I'll have that part of the plan complete, but using a different framework.  That said, I'm now at the point where on the CDK side of things, I want to obfuscate my info like account number in ARNs.  I'll need to dive into what's risky here.
* Day 19: Big day ahead of me outside of code so I snuck in some quick updates.  I'm learning to pay attention to responsive design - it has become a bit of a habit to make sure my project will show up well on mobile devices.  That's good because responsive design is what I have scheduled for the next 3 days of commits!  I've also been doing some reading on Headless Wordpress as a potential solution to adding a blog.  
* Day 20:  More work on the CDK.  I learned how to use Codestar to connect Github to CodePipeline.
* Day 21:  I hear it takes 21 days to create a new habit and here I am!  What a good Day 21 it has been.  I've just completed build the CDK for my portfolio website.  It creates a CICD pipeline and an S3 bucket.  I am running into a deployment failure however, but I'm going to call this a WIN!!!  The deployment failure appears to be some account-level restriction I have on CodeBuild.  I really wanted to see my site deployed to S3, but I'll have to practice patience.  In the meantime, I'll dive further into understanding headless wordpress or other blogging options. - Late update for Day 21: I've been diving into some tutorials using Apollo/GraphQL with Wordpress.

</details>

* Day 22: Added a resume component to the portfolio website, but I'm still waiting on AWS to increase my CodeBuild service limit.  Not sure why it's at 0.  I followed a great tutorial last night about headless wordpress with next.js, but it has be rethinking my architecture.  Should I build a blog as a separate app or not?  While waiting on AWS, I decided to use Amplify instead and that takes care of my basic use-case here.  The website does load, but for some reason, the images don't.    
