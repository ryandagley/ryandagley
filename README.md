- 👋 Hi, I’m @ryandagley
- 👀 I’m interested in building cool solutions on AWS and working with AI.
- I write a ton of SQL at work and I'm looking to expand my knowledge.
- Welcome to my codes.
- Challenging myself to Commit 100 days in a row (some code, some other exploration).
[![GitHub Streak](https://streak-stats.demolab.com/?user=ryandagley)](https://git.io/streak-stats)

Things I'm studying this week:
1. Stable Diffusion
2. AWS Amplify
   
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
* Day 21:  I hear it takes 21 days to create a new habit and here I am!  What a good Day 21 it has been.  I've just completed build the CDK for my portfolio website.  It creates a CICD pipeline and an S3 bucket.  I am running into a deployment failure however, but I'm going to call this a WIN!!!  The deployment failure appears to be some account-level restriction I have on CodeBuild.  I really wanted to see my site deployed to S3, but I'll have to practice patience.  In the meantime, I'll dive further into understanding headless wordpress or other blogging options. - Late update for Day 21: I've been diving into some tutorials using Apollo/GraphQL with Wordpress.  UPDATE: Lessons learned - passing environment variables through the Amplify console works!

</details>

<details>
   <summary> <strong> Week4: </strong> Days 22-28 of 100</summary>
   
* Day 22: Added a resume component to the portfolio website, but I'm still waiting on AWS to increase my CodeBuild service limit.  Not sure why it's at 0.  I followed a great tutorial last night about headless wordpress with next.js, but it has be rethinking my architecture.  Should I build a blog as a separate app or not?  While waiting on AWS, I decided to use Amplify instead and that takes care of my basic use-case here.  The website does load, but for some reason, the images don't.
* Day 23: It has been a busy day at work, but got a little bit of work done during lunch today.  In messing around with the Amplify console, I've now got one github repo deploying to my main domain for the portfolio site and the blog repo writing to a subdomain.  I've learned a lot of ways it won't work and this is the first way that it has.  I may want to revisit this later, but for now I am satisfied.
* Day 24:  I'm getting into the weeds on my blog's amplify deployment.  Everything builds fine locally, but when pushing to Amplify, my environment variables can't be defined.  I've tried a few different ways now and same failure each time.  I'm glad I got ahead of schedule on this because this is a tricky one!
* Day 25: I learned that environment variables can be provided via the Amplify console and my deployment was successful.  I have a lot to learn about SSR because the site doesn't update when a new blog post is published, instead it needs a new deployment!  
* Day 26: I quickly put together an image gallery website following an HTML/CSS tutorial.  I have today and tomorrow to finish up my project showcase pages on the portfolio site before focusing on fixing the blog.  I also have another fun project idea in the works, but don't want to commit too much time to it until I've made sufficient progress on my existing projects.
* Day 27: I built a new Next.js website, mostly from scratch!  Today I learned that capitlization in filenames is not only important, but requires specific handling in Git in order to update the name in the repo.  I spent a lot of time chasing down a problem in my code, when it was a problem of capitlization!  I have a migraine today so even though I'm excited to work on my projects, I probably need to rest up.  I'll be a day behind on finishing touches for my portfolio's project section.
* Day 28: Feeling under the weather today so making a small edit to my Nihonga page, making it less political.  And that might wrap up week 4!  Felt better in the evening so made significant updates to AI Nihonga page.  Learned a lot about CSS today in trying to make the site look how I want it to.  

</details>

<details>
   <summary> <strong> Week5: </strong> Days 29-35 of 100</summary>

* Day 29: 4 weeks complete!  Starting the day off with a small spelling correction before my commute.  Saw that my new site looks odd on Firestick's Prime Silk Browser.  I'm wondering if that's even worth exploring in the responsive space.  UPDATE: it turns out it wasn't just the silk browser and I've had a lot to learn about responsive design.  I think I've fixed it for the most part, but I'm going to call my Nihonga site a good start and not a finished product.
* Day 30:  Wow!  30 days challenge complete!  That feels good!  However, my latest coding project is not going well.  Everything is fine locally, but once deployed via Amplify, I get errors and 500s.  I guess I'll have a lot to learn in troubleshooting this.  Perhaps my first rollback.  We'll see.  
* Day 31: After many attempts, it's time to suck it up and rollback my commits.  UPDATE:  I've rolled back everything to even the first build.  I've even created a new Amplify app with an earlier working build.  Something has gone wrong and I'm thinking of starting from scratch.  I deployed a minor update to my software portfolio site just for a quick sanity check and I'm thankful that didn't fail either.  So far, this has been the most challenging day of my 100 day challenge.  My vacation from work starts tomorrow so I think I'll go enjoy my night.
* Day 32: I've rebuilt my entire site from scratch in a new repo and deprecated the old one.  I still don't know the root cause of the failure so I'm going to assume it was on the AWS side of things.  Lessons learned: 1.) I want to add a stage before prod so I don't suffer downtime again.  2.) I need to add better testing methods.  That said, I now have an fairly straightforward path to making smaller updates throughout my vacation.
* Day 33: Fixed some styling issues throughout my Nihonga site and sent it to my sister and brother-in-law.  Let's call that "acceptance testing."  They thought it looked pretty good.  I'm putting my new and cautious testing/deployment method into practice.  I'm now thinking of using some type of content delivery technology since I don't think it makes sense to keep coding in new images.
* Day 34: A quick and simple edit this morning to AI Nihonga to add an image.  I was up last night in bed reading about Stable Diffusion so I'm installing a local version now to see how capable my home machine is.  I'm interested in training my own models!
* Day 35: Another quick addition to my Nihonga site.  I got Stable Diffusion to run locally on my computer and today I loaded my first image using that.  I learned some Inpainting and a few things about writing prompts.

</details>

<details>
   <summary> <strong> Week6: </strong> Days 36-42 of 100</summary>
   
* Day 36:  September 19th.  I started on August 15th and I feel that I've really developed myself in this time.  This morning I made another addition to the Nihonga site and I'm exploring prompts for AI generation a bit more.  Today, I'm meeting with my nephew (high school senior) to discuss potential careers.  I'm taking a little trip tomorrow so I'm going to learn how to make a commit from my phone as to not break my awesome streak!
* Day 37: Made an update using my phone today!  I just made a direct change to github.  I did not enjoy the experience, but I don't have a good laptop to take with me.  It seems good time to budget for one.
* Day 38: Quick bug fix this morning.  Still working from my phone.  Im going to learn about extending images using Stable Diffusion today.
* Day 39: 9/22 - Added AI Nihonga as a project to my portfolio, but not available yet.
* Day 40: 9/23 It seems that I had some bad routing in my code and the portfolio website also gives 500s.  This is exactly what happened with the Nihonga site before.  I had to deploy everything from scratch in a new Amplify app to fix it last time.  I hope I don't have to do that again.  I believe this is a problem with Amplify over my code.
* Day 41: 9/24 Tried a few corrections to make the portfolio website work.  It didn't.  I assume I'll need to rebuild the whole thing again here soon, but not today.  I think I'll start searching for a new framework that works well with amplify since I don't think NextJS is it.
* Day 42: 9/25 Today's focus was on understanding LoRAs in Stable Diffusion.  Didn't work on code outside of work today, just prompts.  UPDATE: Downgrading my websites Next version appears to have fixed my issue for now.  Amplify seems to be an all around difficult product to use for hosting NextJS sites as this is the second time I've dealt with this issue in a month.

</details>

* Day 43: 9/26 With 14 weeks left in the year, I find myself wanting to take some projects past the finish line.  I also feel the need to revisit my goals as an engineer.  There are clearly some types of projects I enjoy working on, and other projects that I don't.  I should pay more attention to that.  UPDATE: "Drudge through the drudgery."  I came home from work and created a ton of open Issues for my projects.  I then decided to start tackling them!  Tonight I learned how to build an e-mail button that obfuscates my email address to the Amplify environment variables.  This allows people to contact me, but cuts down on the bot spam (I hope!).  UPDATE 2:  Resolved some issues, but opened up many more.  Today has seen more contributions than any other day so far.  Done for the evening feeling satisfied in what I've accomplished.
* Day 44: 9/27 Looking back on my projects so far, I need to start leaning into the back-end, but having too much fun building front ends.  I'll start working on making my Portfolio's contact form functional.  I'm thinking Lambda, SES, and CAPTCHA will be included.
