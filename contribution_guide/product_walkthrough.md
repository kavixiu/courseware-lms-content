# Contribution Guide: Product Walkthrough
 
### Step 1. Fork this repo!  
### Step 2. Review the video details, example video and example script: 

| Description | A product walkthrough video is a high level video that takes the viewer through an overview of key product features; describes the value of the product and a quick glimpse into how it works.
| --- | --- |
| **Presentation** | Command-line screencast along with voiceover narration. <br>Contains title card intro and Puppet-brand animated outro. |
| **Length** | Up to 10 minutes. |
| **Quality/Tone** | Friendly and authoritative. Narrated directly, in 2nd person (i.e. "Now click on the link" as opposed to "Now *we* click on the link" or "Now *I* click on the link". For more details on tone, defer to the [Puppet Content Style Guide](https://confluence.puppetlabs.com/display/Writing/Tone).)
| **A/V Recording Settings** | See [Puppet Training Videos: Best Practices](https://confluence.puppetlabs.com/display/SP/Puppet%27s+Training+Videos%3A+Best+Practices), [How to record audio and video for a screencast](https://confluence.puppetlabs.com/display/SP/How+to+record+audio+and+video+for+a+screencast) and [Audio Recording 101](https://confluence.puppetlabs.com/display/SP/Audio+Recording+101). 

<br>

### Product Walkthrough Video Example 
[![Puppet Tasks Product Walkthrough](/contribution_guide/example_screenshots/Puppet_Tasks_Product_Walkthrough.png)](https://puppet.wistia.com/medias/o4nlwajf0y)
*Video example does not perfectly match script example - defer to script example when writing your script.*
	
<br>
	
### Product Walkthrough Script Example 

Order | Section | Description | Length | Narration | Example Timecode
----- | ------- | ----------- | ------ | ------- | -----
1 | Title Card | State your name and title for the intro title card. | 1 sentence | *"My name is Eric Sorenson and I'm the Director of Product, Ecosystem and Platform at Puppet."* | 00:00-00:03
2 | Value Proposition | Introduce the value of the product features and explain what the problem is that it solves. Give an example of a real world case study | 1-3 sentences |  *"Puppet Tasks are a way to solve problems that don't fit well into Puppet's traditional model... Sometimes you need to fix things that are more like a pont-in-time change..."* | 00:06-00:57
3 | Video Overview | Provide a video overview. | 2-4 sentences (narration) AND 2-4 bullet points (visual) |  *"In this video I will get the tool installed, learn how to run single commands and scripts with it, and then learn how to turn scripts into tasks."* **Bullet points: Install tasks tool, Run single commands and scripts, Turn scripts into tasks** | 00:57-01:10
4 | Training Content | Walk through the training content. This is the meat of the content, containing all the navigation, concepts, links, step-by-step processes, etc. | 5-8 minutes |  *"The standalone task runner is called Bolt. Its written in Ruby, distributed as a gem, and I'm going to get started by installing Bolt on a workstation with the command 'gem install bolt'..."* | 01:10-06:21
5 | Video Recap & Resources | A very brief recap about what the viewer has learned, and resources for where to find more information or people who can answer additional questions. | 3-5 sentences |  *"(In this video I) ran commands using the Bolt tool, then took those commands and turned them into a script, which was transferred to the remote systems and executed. I then turned the script into a task which let Bolt learn more about how the task was written and run it with parameters... "* | 06:21-06:55

<br>
<br>  


### Step 3. Add your content to the script placeholder form below: 

Order | Section | Description | Length | :arrow_down: ADD YOUR CONTENT HERE :arrow_down:
----- | ------- | ----------- | ------ | -------
1 | Title Card | State your name and title for the intro title card. | 1 sentence |*"My name is ___ and I'm the ___ at Puppet."* | 00:00-00:05
2 | Value Proposition | Introduce the value of the product features and explain what the problem is that it solves. Give an example of a real world case study | 1-3 sentences |  *"The ____ is a (tool/process/product) built to help you _____. (Insert real world case study here)."*
3 | Video Overview | Provide a video overview. | 3-5 sentences (narration) AND 2-4 bullet points (visual) |  *"In this video I will (overall video intention). First, I will (agenda item 1), then I will (agenda item 2). Next I will (agenda item 3). Lastly I will (agenda item 4)."* **Bullet points: Item 1, Item 2, Item 3, Item 4**
4 | Training Content | Walk through the training content. This is the meat of the content, containing all the navigation, concepts, links, step-by-step processes, etc. | 5-8 minutes |  *"(Start with agenda item 1. Then move on to item 2, then item 3, and so on...) "*
5 | Video Recap & Resources | A very brief recap about what the viewer has learned, and resources for where to find more information or people who can answer additional questions. | 3-5 sentences |  *"In this video I covered (agenda items/key takeaways, in order of presentation). (Your personal sign-off, including any additional resources and contact information if applicable.)*"

<br>

### Step 4: Delete everything above your script. Submit a pull request to have your script pulled into the 'transcripts' folder here: https://github.com/puppetlabs/courseware-lms-content/tree/master/video/transcripts.

<br>

✨You did it!  :dancers:✨ Now you're ready to record your screencast. [How to record audio and video for a screencast.](https://confluence.puppetlabs.com/display/SP/How+to+record+audio+and+video+for+a+screencast)
