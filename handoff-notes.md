 # Developer handoff notes

# Developer handoff notes

## What I delivered
I built a customer support page for Northstar that shows the support email address and the support hours in Central Time.
I also added a reminder to include an order number and an FAQ section because customers kept asking about how to check their order status.

## How I verified the page
I opened index.html in my browser and checked that the title, contact email, Central Time support hours, order number reminder, and FAQ were all visible.
I also made the window narrow and the page was still readable. All checklist items passed.

## Remote change I received
A teammate (simulated on GitHub) added a Support escalation section to the README explaining that unresolved billing requests go to the billing team after one business day.
I brought it into my local copy with the command git pull --ff-only origin main.

## Git workflow explanation
After git commit, GitHub did not change because a commit is only saved in my local repository on my computer.
To send my commits to GitHub, I had to run git push origin main, which uploads my local commits to the remote repository.