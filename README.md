- 👋 Hi, I’m @ryandagley
- 👀 I’m interested in building cool solutions on AWS and working with AI.
- I write a ton of SQL at work and I'm looking to expand my knowledge.  
- Welcome to my codes.
- Challenging myself to Commit 100 days in a row (some code, some other exploration).
[![GitHub Streak](https://streak-stats.demolab.com/?user=ryandagley)](https://git.io/streak-stats)

Things I'm studying this week:
1. Tkinter
2. Wordpress
   
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
* Day 42: 9/25 Today's focus was on understanding LoRAs in Stable Diffusion.  Didn't work on code outside of work today, just prompts.  UPDATE: Downgrading my websites Next version appears to have fixed my issue for now.  Amplify seems to be an all around difficult product to use for hosting NextJS sites as this is the second time I've dealt with this issue in a month. UPDATE: I've set up a reCAPTCHA, but haven't done anything with it yet.  Needed some rest to avoid burnout. UPDATE: Felt like adding some details to one of my project pages.  Can't figure out a logo design that I like.

</details>

<details>
   <summary> <strong> Week7: </strong> Days 43-49 of 100</summary>

* Day 43: 9/26 With 14 weeks left in the year, I find myself wanting to take some projects past the finish line.  I also feel the need to revisit my goals as an engineer.  There are clearly some types of projects I enjoy working on, and other projects that I don't.  I should pay more attention to that.  UPDATE: "Drudge through the drudgery."  I came home from work and created a ton of open Issues for my projects.  I then decided to start tackling them!  Tonight I learned how to build an e-mail button that obfuscates my email address to the Amplify environment variables.  This allows people to contact me, but cuts down on the bot spam (I hope!).  UPDATE 2:  Resolved some issues, but opened up many more.  Today has seen more contributions than any other day so far.  Done for the evening feeling satisfied in what I've accomplished.
* Day 44: 9/27 Looking back on my projects so far, I need to start leaning into the back-end, but having too much fun building front ends.  I'll start working on making my Portfolio's contact form functional.  I'm thinking Lambda, SES, and CAPTCHA will be included.
* Day 45: 9/28 Today is going to be a bit more visually focused.  I'm not thrilled with the images and logos I'm using across multiple projects.  I think I'll spend some time in Stable Diffusion and Canva tonight to add a bit more flavor to my websites.  My focus at work today was a bit more DevOps and SQL heavy.  I think I'll have a snippet of code to add to my SQL repo when I get home.
* Day 46: 9/29 I learn more about which NextJS problems caused deployment errors when they don't show in npm run dev.  That said, I've created a bit of a template for how I want my project pages to look.  I feel that my portfolio website is starting to work a lot better.  UPDATE:  I'm excited that tomorrow, I will have made commits for a full calendar month!  This practice sure has helped me to start looking at my career in software engineer a little differently.  I really am grasping the power of practice.  Yesterday, I started listening to the Pragmatic Programmer audiobook.
* Day 47: 9/30 Today's focus was on making my web portfolio feel more complete.  I've finally got some logos that I feel better about and added some functionality with responsive design in mind.  My coworker the other day pointed out that my main focus on these sites appear to be web design over front-end engineering so that's got me thinking about some projects (also gave me a little bit of imposter syndrome, but that's ok).  I've got a wedding to go to!  I'll have to deal with all that at another time.  UPDATE: I've transferred over my namesake DNS - my old provider still tried to bill me an additional $100.  Their excessive billing is a main reason for why I'm headed to AWS with my projects.  Also, as far as milestones go, this is my first full calendar month of commits!  My next milestone is in 2 days, the halfway mark.
* Day 48:  I've knocked out a ton of open issues on my web portfolio.  I feel like the site is started to capture more of what I want to present.  I'm looking forward to getting to the point where my focus shifts over to the smaller projects that the portfolio is meant to showcase!  
* Day 49:  I've got a touch of the Covid, but spent a little bit of time figuring out some problems with Lightsail.  I learned to apply HTTPS to my wordpress instance, but I still have not been able to figure out why images don't load in my blog posts.  It's a tricky one!

</details>

<details>
   <summary> <strong> Week8: </strong> Days 50-56 of 100</summary>
* Day 50: 10/3 Still ill.  I've decided to build a workaround to my headless wordpress issue in the meantime by making sure that my blog looks good as a standalone wordpress instance.  https://dagleyblog.com is now live.  Anyway!  Day 50!  I'm halfway to my goal.  This is really excellent.  I feel like I've learned a lot on the way, but I'm also uncovering how much I don't know.  In this second half of the streak, I'll need to fix my bugs and I plan to get Mycologeek going again starting with a new deployment plan.
* Day 51: 10/4 As a matter of practice, I used Amazon Lightsail and Route 53 today to route a new wordpress blog to a HTTPS DNS.  This involves updating namespaces, grabbing a static IP, and finally setting up HTTPS in Bitnami.  At work, I wrestled with some SQL - in SQL, I use "HAVING" far less frequently than just about anything else.  However, "HAVING" was a big reason for why I didn't pass an interview many years ago.  Now that the work day is wrapping up, I wonder what I'll get into tonight.
* Day 52: 10/5 - Did a bit of lunchtime coding.  I've been using AI to generate images that are in grids of 4.  I was splitting these manually and wasting time so I learned to build a tool to split them using Python and the Pillow library.  It's in my image-tools repo.  I forgot to update last night, but started using Github Actions to try to deploy to Elastic Beanstalk for Mycologeek.  I'm running into problems, but I'll get there.  I'll probably put it down until the weekend though.
* Day 53: 10/6 - Last night I watch a few videos about what's possible using generative AI.  I'm so fascinated by it!  From making music videos to fake influencers, I'm intrigued.  As for this morning, I have a little bit of time before work so I want to build an interactive mode for yesterday's image splitter.  It essentially opens a window to allow me to select the image I want to split.  This is my first exploration into tkinter and I'm learning to respect what it takes to build a visual product from code!
* Day 54: 10/7 - I've got a big day ahead of me so only a small code change today.  I'll be out in the world searching for mushrooms and inspiration for my projects (I can't let AI do everything!).  UPDATE: In the image splitting tool I had a hard time seeing the images I was working with so made a percentage based thumbnail.
* Day 55: 10/8 - Another small change (bug fixes) so far today as I've made myself more busy than intended.  While I feel a little bit of guilt about it, if this is streak is going to work, then anything has to count!  I typically come back later anyway once I have more time in my day.
* Day 56: 10/9 and closing out Week 8!  Had a tough time figuring out how to correct highlight a selected imagine in my python image splitter app.  I realized that I kept trying to highlight a thumbnail image before it was resized.  

</details>

<details>
   <summary> <strong> Week9: </strong> Days 57-63 of 100</summary>
* Day 57: 10/10 - Made my image splitting app a little more user-friendly with a multi-select and deselect handling.  It's interesting to me that everything needs to be accounted for in building this.  From selecting images to adding a scrollbar, nothing is just done for me.  I'm there's a library that handles that, but doing it the harder way gets me thinking.  That said, this afternoon I'm dealing with a spot of imposter syndrome again.  I wonder what it is.  Who is expecting me to have made more progress?  I think that's something to explore.
* Day 58: 10/11 - Added a Deselect Function to the Image Splitting app.  I thought it would be a matter of resetting the entire app, but learned that it made more sense to just clear the list of selected images and delete the highlights.  I've taken this app further than I had really planned to.
* Day 59: 10/12 - I wanted to try something new today so I came home and put together a quick python application for training me on learning the notes on the guitar neck quickly.  The application gives a Note, then gives a few seconds before showing multiple locations of that note.  I think I'll expand on this.
* Day 60: 10/13 - I can't believe we're at 60 days already!  2 months of daily commits!  Today I learned a little bit more about Tkinter and blocking functions.  In my Guitar Neck Training application, I wanted to start showing the Notes/Answers in a GUI instead of the terminal.  Everything was looking good, but I couldn't move the window around which was annoying.  I learned about Tkinter's "after" which allowed me to move it around.  I like this so far, but I'll have to go and add more positions to the fingerboard mapping.  I'm also thinking of adding some features to allow selective string training too.  It's Friday the 13th in October!  Be safe out there!
* Day 61: 10/14 - I was excited to test out my guitar neck training app and found that I had entered a ton of incorrect mappings!  Shows how that I probably need to do a bit more testing before pushing.
* Day 62: 10/15 - Continued with a few more updates to the mapping.  I'm thinking of abstracting the note_mapping away from the main application for better organization.
* Day 63: 10/16 - I moved the notes of the guitar neck trainer into its own file.  I also corrected an inconsistency in note sizing.  I'm having a challenging time pausing on just the Note part of the app, but it otherwise seems to work on the response.  I can live with it for now - I am using it in my guitar practice!  And so far, that's a wrap for Week 9!  6 weeks to goal!

</details>

<details>
   <summary><strong> Week 10: </strong> Days 64-70 of 100</summary>
* Day 64: 10/17 - I don't have a lot of patience for working on my application today so I quickly created cancel functionality for the guitar app.  I couldn't figure out why tk destroy wasn't the right way to go, but used window.quit() instead and it worked fine.  I explored some options for if I wanted to host this app on AWS.  I'm considering a container on Fargate.
* Day 65: 10/18 - I created a Dark Mode toggle for the guitar app.  It was a bit frustraing knowing to set the background color of the label and the window.  I fell down some highlight text rabbit hole, but the solution was just to configure the background for both the window and the label.  My boss asked about my interest in becoming an SDE today.
* Day 66: 10/19 - I supposed sometime between today and tomorrow, I'm 2/3 to my goal of 100 consistent days!  Today at work, I'm diving deep into the world of AWS Step Functions.  Unfortunately, I'm not build anything, but I'm running tests that consist of many state machines in sequence.  I'll probably be doing a lot more of this in the short-term.
* Day 67: 10/20 - I am solidly in the final 1/3 of this experiment.  What did the first 2/3s teach me?  For one, I have a lot of ideas that I want to explore and that I also lack some focus on what I want to do with my skills.  Second, is that consistent work toward a goal will get you closer to reaching that goal much more than only working on it when you have the motivation.  Working at something consistently removes time as an issue so you learn to enjoy the process.  So for today's commit, I wanted to limit the guitar trainer to just a few notes before closing.  This is the lay some groundwork for allowing the user to define how long they want to test.  
* Day 68: 10/21 I only have time for a quick update today.  I learned about Tkinter's simpledialog which is a module that provide an easy way to display messages and have the user submit input.  I add an input to limit how many rounds a user want to be tested on the guitar training app.  I've introduced a small counting issue by doing that, but I'll address that next.
* Day 69: 10/22 On the guitar app, addressed the counting issue and I'm working on refactoring and moved the stop_app function to its own module.  I was stumbling on this as I was forgetting to import Tkinter into the new module and the errors I got were completely ambiguous.  Busy day ahead of me, but maybe I'll find time to revisit today.
* Day 70: 10/23 I needed a password protection script for Windows since my options to do so were grayed out so I wrote one up using a 7zip library.  It's a bit on-the-nose, but it does its job.  I think that'll wrap up week 10!

</details>
   
* Day 71: 10/24 I wrote a quick python script to take a copy/pasted CSV result from Datagrip and converts it to a markdown table.  I was creating this manually at work and decided it was time to automate it.
* Day 72: 10/25 I used the above script for work and realized that ID numbers were also getting commas so I updated it.  I was challenged on the purpose of this script by an engineer at work since one could just copy to markdown in our chosen IDE, but that doesn't apply commas making it harder to read.  I'm learning that sometimes I'll need to be a strong advocate for what I do.  Tomorrow is another day!
* Day 73: 10/26 Really challenging day at work with a shift in priorities!  That said, I still found some time to code tonight, but finding an annoying issue with my CSV to Markdown script.  I need to better handle for null values and it seems to intermittently detect when a value is null.  I'm trying to do a string modification on it and I believe at this point that's the wrong path.  I'm sure I'll have it figured out this weekend.
* Day 74: 10/27 Today is my birthday so I had the grim idea to write a countdown clock to when I turn 76, the average life expectancy of an American man.  I pondered the thought that "we are what we repeatedly do."  I'm grateful to be putting in the effort now to explore my creativity through code.  I think I'm getting faster at going from concept to working model for simple scripts.
* Day 75:  3 quarters done!  Speaking of progress, I created a progress bar GUI to show how much life left in percentage until I'm 76.  Apparently, I have about 46% of life left to live.  Nice!  I also clean up my code a bit from yesterday, I realize that had confused time elapsed with time remaining.  Don't ask me to be your doctor lol!  Now that I'm really feeling like I'm nearing the final stretch of 100 days, I'm wondering what I'll do after 100 days.  Maybe I'll take a week off and go for shorter streaks like 30 days at a time focused on specifics like Javascript, or maybe even Java!
