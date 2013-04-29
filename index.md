---
layout: narrow_page
screenshots: 
 - /images/old_screenshot_1.png
 - /images/old_screenshot_3.png

---
## # [sup](https://github.com/sup-heliotrope/sup/)
[Sup](https://github.com/sup-heliotrope/sup/) is a console-based email client for people with a lot of email.

It presents an interface of a list of threads, which are each hierarchical collections email messages.
Threads can have multiple tags applied to them.
It supports a very fast full-text search, automatic contact-list management, custom code insertion via a Ruby hook system, and more.
If you're the type of person who treats email as an extension of your long-term memory, Sup is for you.

{% for shot in page.screenshots %}
<a href="{{shot}}">
  <img src="{{shot}}"/>
</a>
{% endfor %}

## # Features
 * Handle massive amounts of email.
 * Fast, local full-text index of messages.
 * Mix email from different sources: mbox files and maildirs.
 * Instantaneously search over your entire email collection. Search over body text, or use a query language to combine search predicates in any way.
 * Handle multiple accounts. Replying to email sent to a particular account will use the correct SMTP server, signature, and from address.
 * Add custom code to handle certain types of messages or to handle certain types of text within messages.
 * Organize email with user-defined labels, automatically track recent contacts, and much more!

## # Sub-projects
### [sup](https://github.com/sup-heliotrope/sup)
[sup](https://github.com/sup-heliotrope/sup) is the original curses email
client, full-text index, and hook system.

### [Heliotrope](https://github.com/sup-heliotrope/heliotrope)
[Heliotrope](https://github.com/sup-heliotrope/heliotrope) is an architectural
shift from sup that maintains many of the same concepts, but separates out a
server and client.
Contrast to what is done in sup, where one large client installation has all
the mail documents and indexes locally, Heliotrope provides a server-side
service that indexes mail.

In this way, remote clients can connect up and interact with their mail stores
in a sup-like way, while keeping the mobile install slim.
This is a lifesaver when switching from machine to machine.

### [Turnsole](https://github.com/sup-heliotrope/turnsole)
[Turnsole](https://github.com/sup-heliotrope/turnsole) is an example client
that would connect to Heliotrope and interact with mail.

### Resources
 * [wiki](https://github.com/sup-heliotrope/sup/wiki)
 * [Issues](https://github.com/sup-heliotrope/sup/issues)

### Authors and Contributors
Sup is brought to you by [a cast of hackers.](https://github.com/sup-heliotrope/sup/blob/master/CONTRIBUTORS)
