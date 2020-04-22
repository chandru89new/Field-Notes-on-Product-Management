# On Organizing Information

## Pick a tool, but don't overtool yourself

Management tools are a means to a specific end. Mostly, the end is about organizing information in a way that it's easy to access and update.

Even a simple spreadsheet for task management is okay as long as you're able to spend less time toggling information and more time building. Personally, I've had much success with kanban (I use Trello or JIRA) because it is convenient to view your day-to-day activities as a bunch of todos.

Don't fall into the try-every-new-tool trap. A few large-scale open-source projects still use IRC instead of Slack and not only get by with it but are doing pretty good.

## Work communication as an extension of todos

When task-related communication happens in Slack channels, details of how something got implemented (and why) get lost in realms of chat threads.

Just one switch helped me solve this (to a good extent). I switched task-related communication from Slack to the todo ticket. Any discussion about the task would happen only on the ticket. (That means, even if the developer asked a question on Slack, I'd prod them to post the same on the task card). 

There are some instant benefits to this: because it's now a comment, developers think deeper and write clearer. And you have a stack-trace of why something got implemented the way it did.

## Early workflows, evolutionary refinements

Setup your workflows early in the day. Don't wait for (a) a complete understanding of a system (say, kanban), or (b) the perfect critical mass for your team or workload. 

Adopt a system - like kanban or GTD - early. No system, in its original state, would answer all your needs anyway.

That means you have to continually refine your system over time as you find the holes that don't fulfil your specific environment.

Eventually, what happens is you adopt a system and then, even unbeknownst to you, you'll refine it and make changes to it to suit your needs.

##. Public chats vs. Private messages

When developers ping privately and it is a question about a feature or bug, try to get them to post on the group. This way, you make discussion de facto. I've sometimes been saved by this because someone points out something that I (or the dev who posted the question) had not factored in.

It also saves time when, to answer someone's question, you need inputs from others. Instead of quoting the question again to give the others a context, you can simply start with your question. The context is already visible for everyone else.
