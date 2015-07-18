# SIGNAL

## PnS

Problem: High number of users who start articles but leave

Solution: Provide an obvious way to allow users to reengage
***

Problem: Users do not want to sign up to service

Solution: Use a service they are already using to reach them.
***
Problem: You dont know what service the user uses to get reminders about stuff.

Solution: There are some services that have a higher penetraion rate for usage. Start with email, then move to other services that are more common.
***
Problem: The platform doesnt want to build the stack to allow users to get remined of content.

Solution: Create a service that services can use to reengage users.
***
---

## WWWHW

What: Webpage tool to allow users to subscribe to reminders to read content they have previously expressed interest in.

Who: Anyone who is good at finding content, but not so good at providing enough time to explore the content.

When: After a user has shown their interest in content, display a way for them to subscribe to an email reminder.

How: Use javascript to monitor use behavior and wait for a behavioral match to trigger reminder offer.

Why: We want our users who find content they life to comeback. Because there is so much content made, but it gets buried quickly.

---

## Value

Increase page view
- [+] people come back
- [+] create recirc in the email	
- [+] sell more ads
 
Increase number of uniques
- [+] new devices, same person
- [+] track people across devices	
- [+] sell more ads

Target KPI
- [+] Push over paywall
- [+] Increase "high value" user
- [+] Increase value of ads
	
Increase input from subscription funnel
- [+] More people hit paywall
- [+] More people subscribe
- [-] Potentially change the mechanics of subscription funnel

---

## Plan

1. Set up an email server
	1. Transaction rules 
	2. Delay system
		1. [subscription option] Send to me later
	3. Reminder system	
		1. [in email] I dont want to read it yet
2. Create a template system to send out reminders
	1. Populate content
	2. Get recirculation recommendations
		1. Choose content based on user browsing
			1. Cartoons, blogs, photos, video
		2. Update new templates for reminder system
3. Design the on-page experience
	1. Signing up
	2. Getting confirmation
		1. Changing setting
	3. Setup how to trigger on
		1. Scrolling up
		2. Scrolling down fast
		3. Leaving page
		4. About to bounce
		5. Post bouncing, before finishing
			1. Go to another article, after starting one
			2. Offer to continue other article at another time
