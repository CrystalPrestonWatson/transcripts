# Automation and Accessibility - What You Need To Know

Crystal Preston-Watson:
Automation and Accessibility. What You Should Know.

Crystal Preston-Watson:
I want to tell you about things you won't find in this video. This is not a Digital Accessibility 101. A foundation in digital accessibility is necessary. Well, required for accessibility testing. Today, I focus on higher level questions and issues that teams need to consider before beginning accessibility automation. That also means I won't be doing any coding or demoing any tools. However, I will provide links to many of the items and resources I discussed today. If you feel that you don't have a solid understanding of the basics of digital accessibility, I encourage you to come back to this video after learning a bit more. I'll be right here waiting. Well, not me. This is a digital version of me. I don't live in this video. I'm not the girl from the ring.

Crystal Preston-Watson:
Let's get started by going over to three types of accessibility testing. Manual accessibility testing is when teams test applications for accessibility issues that may cause problems for users with disabilities. This testing is conducted using browser and plug-in tools like Wave, Lighthouse or Ax. Also assistive technology like screen readers and switches. Currently on the screen, I have a slide that has several logos for automated tools, Wave, Lighthouse and Ax and screen readers, JAWS, and NDVA. Also an image of two jelly bean switch devices.

Crystal Preston-Watson:
Automation accessibility testing is my focus today. You might wonder why I listed some semi-automated tools under manual instead of automation. While many of those tools can be fully automated, their browser extensions are widely utilized in manual testing. This slide showcases three logos, Ax, Applitools and Espresso. VQS axe-core powers a considerable portion of free and paid accessibility tools and automation frameworks. Applitools contrast advisor validates color contrast ratios for text and graphics, and can be integrated into existing automation frameworks. Espresso is an Android UI testing framework that has integrated accessibility checks.

Crystal Preston-Watson:
User acceptance testing gets overlooked by companies when it comes to accessibility. Testing with people with disabilities is necessary to understand how your application performs in the real world and finds issues and bugs beyond accessibility conformance. This testing needs to be done with more than one person or a group with a singular disability within your target audience. Also, make sure that it is paid. People's time is worth money. And given that this testing can find some very costly bugs, it's worth more than free software.

Crystal Preston-Watson:
Part one, are you ready to automate? I ask people who tell me that their testing team wants to automate their accessibility testing if they're ready. I don't want to answer, but them to reflect on their current accessibility initiative. There's a vast difference between wanting to automate and being prepared and able to automate accessibility. Many teams like to focus on technical readiness. But with accessibility, two significant considerations must be addressed before a framework is selected or code written to make automation successful. Let's take a look at those now.

Crystal Preston-Watson:
Experience with accessibility. Accessibility is not an intentional undertaking for many teams. As my grandfather liked to say, "They fall ass backward into it." A demand by company leadership in response to customer concerns, complaints, or even ADA lawsuits. There's an enormous scrambling to inventory accessibility in their products. There's no time for preparation or ramp up for training or education. The issue compounds with the realization that accessibility has prominence on manual testing. So there's pressure to automate ASAP, to make testing quicker and more effective. You can't see me, but I did make air quotes when saying effective.

Crystal Preston-Watson:
Don't get me wrong. I am on board with test automation. When done right, it increases productivity and requires a smaller time investment. But the magic words, when done right. That doesn't happen with teams that do not have a solid foundation in digital accessibility. A team that struggles to interpret and test against web content accessibility guidelines, let alone understand how disabled people use assistive technology devices to navigate their digital applications. In my presentation, after the audit, I suggest action that teams can take to develop accessibility skills and experience to integrate into their testing process. Here are a few of those actions.

Crystal Preston-Watson:
Establish a baseline of knowledge. It's essential to create a shared language and understanding when discussing accessibility and disability. This allows you to effectively communicate the why and the how to go through testing. Encouraging teams to learn through courses, attend conferences, coaching, and providing team training on core fundamentals.

Crystal Preston-Watson:
Play to people's strengths. Put people in the task that best fit their experience. If someone is apprehensive about testing using screen readers, while you need them to have that knowledge, let them focus on keyboard testing while they skill up with other assistive technology.

Crystal Preston-Watson:
Shifting accessibility to the left. It's common for testing teams to become the sole champion of accessibility within a company. For accessibility to be a priority, it has to be the concern of the whole organization. That means promoting and informing stakeholders in leadership that accessibility can't be tested away and needs to be a good company wide priority. This last action leads me to the second consideration for being automation ready.

Crystal Preston-Watson:
Capacity and support. As I mentioned, testing teams often become the sole champion of accessibility. Unfortunately, it is considered an afterthought or nice to have instead of a necessity. This is similar to some opinions about QA and testing, especially when it comes to manual exploratory testing. I was at QA for nine years and I'm all too familiar with the devaluing of testing. It's not shocking to see testing teams become the facto owner of accessibility. But given the individuals situations and circumstances affected by inaccessibility of products, this cannot be left up to tech debt and a one off crunch sprint. Here are three items you should evaluate to see if you have the capacity and support to begin automation.

Crystal Preston-Watson:
Everyone is onboard. Onboard and taking up appropriate roles when it comes to accessibility. This is why it needs to be a company wide priority, with backing and training and education for everyone. If the company accessibility initiative is just testing, then it's a failed initiative and no automation will make up for that.

Crystal Preston-Watson:
Ongoing manual testing. I'll get into the particulars later. But manual testing cannot be automated away from accessibility. Automation and manual here are genuinely mutual. If you have the headcount for both, that's great. But if you don't, then manual is the one that needs to continue.

Crystal Preston-Watson:
Keeping regression in mind. Regression and accessibility can be problematic. Mainly surrounding when bugs and issues are found due to audits conducted by third party vendors. It's essential to make sure bug fixes due to audits and other avenues make it into your regression testing. It's not unusual to find the same bugs with every new audit because regression test cases never make it into the in-house regression suites.

Crystal Preston-Watson:
If you aren't frozen in existential dread after considering what it means to be automation ready, congratulations. You're probably ready. But hold on before breaking out that code.

Crystal Preston-Watson:
Part two, what should you automate? Accessibility automation will not find everything. Most accessibility experts agree that only 20 to 40% of accessibility issues are found with automation testing. Combining manual and automation is a balance and a holistic approach to accessibility testing. Teams might be reluctant to add manual testing for accessibility, especially if they're heavily automating in other areas. But manual testing is unavoidable for catching accessibility issues that automation cannot detect. Let's look at areas where you can enhance your accessibility testing with automation. And what should be left for manual.

Crystal Preston-Watson:
Unit and integration. Unit and integration tests are perfect for accessibility automation. This is where you can detect low line bugs that take a vital time during manual testing and can watch for regression. This also allows you to incorporate accessibility into continuous integration builds. Some of the things you would want to focus on in unit aggression would be … and I would like to credit Marcy Salton for this list, unit testing, component specific behavior, interaction and focus APIs, ARIA states. Integration, real world browser testing, document and page level rules, color contrast.

Crystal Preston-Watson:
UI. I don't usually encourage UI automation for accessibility. UI tests are known to be flaky due to frequent adjustments and changes. My personal experience and opinion is that time can be spent creating either unit and integration or can't and shouldn't be automated and needs to be tested manually. But if you want to have UI automation, here are two scenarios that tend to work best. Multi-page workflows, form flows.

Crystal Preston-Watson:
Manual. An automation framework cannot make subjective interpretations, whether something is or isn't accessible. Also when it comes to assistive technology, it's either impossible or not practical to automate their operations. The heart of accessibility is human spirits. This is why manual testing is priceless and a necessity for accessibility. Here are some of the areas that you would want to focus on. Keyboard interactions, assisted technology devices, caption, transcript, and alt text quality, error identification.

Crystal Preston-Watson:
Part three. So are you ready to automate? At the beginning of this video, I said that there's a difference between wanting to automate and being ready to automate accessibility testing. So I ask you, given all I've discussed, your team's experience with accessibility, your capacity and your support from within your company. Are you ready to automate your accessibility testing? Again, I'm not expecting an answer because I'm not here. This is the digital version of me.

Crystal Preston-Watson:
If you take anything away from this talk, let it be this. Accessibility goes beyond design, code and testing. It's about humans and their experiences. And accessibility is a human and civil right. If you have any questions on the information that I presented or want links to many of the items and resources I discuss, you can reach me via Twitter @ScopicEngineer or my website, CrystalPrestonWatson.com.
