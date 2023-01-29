**Tuesday: Scrum Master Victoria** 💪

# Stand-up:

Looking to wrap up front end deployment AM, and then move onto bug hunting and fixing PM.

Possible solution that did NOT work: created new file in root called netlify.toml with the following contents, which tells Netlify how to build:

- had written linux with capital L instead of lower case

NB: Chances are, netlify is running on Linux containers, and these are case sensitive. This can make deploying from windows machines difficult because every case has to be PERFECT! And it won’t necessarily throw an error in local machines.

# Retro:

Nailed the deployment! Dynamic search feature is completed and deployed. Found some bugs after deployment → one with dynamic search. Still some tickets to mop up tomorrow with styling and positioning etc but functionality is more or less wrapped up. 4pm we reconvene to decide on presentation details.
