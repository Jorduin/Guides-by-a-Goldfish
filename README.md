- 👋 Hi, I’m @Jorduin, Jordan Anders
- 👀 I've been learning zVM and decided to share the tools I made for myself to help guide me through administrative and installation tasks.
- 🌱 I'm currently working on zVM 7.3 and learning about SUSE.
- 💞️ It is my hope that these guides will provide usable rails for others to get from Point A to Point B, learning via first-hand experience 
      rather than simply reading about a task.
- 📫 Message me here on Git if you have issues, questions, comments or concerns. I will also provide my email if asked.
- ⚡ Fun fact: At the time of writing these guides I had a year or less experience with zVM and previously worked in unrelated fields. I found
      getting information about zVM to be cumbersome as IBM PDFs are neither guides nor manuals but instead an odd ghoulash of the two. This is
      more comprehensive than what I've written but also muddies the water in my opinion for both experienced users as well as new. I hope that
      these simplified guides can serve as instructions, as well as training material for those just looking to learn. 

**IMPORTANT**
Check your shop's zVM version to be sure it is on 7.3 when following general instructions and understand that the, "Second Level Upgrade" instructions
are written for a system that was on 6.4 moving to 7.3. Confirm with changelogs the differences between your own version and 7.3 if it is not 7.3
and take into account anything that may have moved, been renamed, removed or changed in some way as this can have unexpected impacts.

**IMPORTANT**
Some commands are more powerful than others and can have devastating results. Please remember to submit those with as much protection as possible.
If you need to edit System Config for example, make a copy and edit the copy. Then replace the active System Config after you've done checks.
If you want to use Define MDISK, do so from a sandbox and preferably *to* a fresh second level OS that is not IPL'd. Without these layers of protection
the possible damage is great.

For the best training experience try treating these as a group as though they were a workbook with activites to be completed. Perform these tasks from
within a sandbox to keep dangerous commands away from production and be certain that devices you would not want to accidentally affect are not
sensed or set to be brought online. Use these documents as a guide, and the IBM documents as manuals. One to show you the way, and the other to
tell you about what you'll pass along the journey with details.

I didn't receive direct training when starting zVM, so what I had to work with were the official IBM documents. These contained a lot of info I
didn't understand at the time that got in the way of trying things out. It was hard to identify what was useful and what could wait to be 
defined, researched etc. What I did get were helpful suggestions and advice for tasks to perform or projects to undertake. For example a 
coworker would be say, "Hey it would be cool if we had a Batch File System (BFS)." So I set out to set up and play with a BFS. I would first
do my best to bumble through the task- copying the entirety of any text that mentioned BFS from the IBM documents and cutting (Ctrl+X) anything
I didn't immmediately understand into a separate document for researching and defining. I would then take the usable portion and whatever commands
were provided and attempt the task until I could reach the end without errors and test the system. Once I could do this I started over and recorded
the process with OBS Studios. I then take the video and watch, marking down a numbered lists of succinct step/task descriptions. Then passing over
each task I would add detailed steps and snip images from the video to provide context. Once everything was written in plain text, another pass
to add syntax structure and command examples, finally another pass for color coding and clarity. Afterwards I handed the guide off to another person
to point out anything confusing and elaborate.

I do not intend to continuously update these. Feel free to download, modify or customize them as you see fit- all I ask is I be mentioned. The DRCT
Execs were written by Alan Wise, credit for those go to him.
