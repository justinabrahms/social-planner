# Social Planner

Coordinating and remember to hang out with multiple groups of friends
can be difficult. I'd like a tool which will prompt me to schedule
things with people who I've not spoken to in a while.

# Thoughts

To do this, it seems like we'll need a few things.

## List of people

We need the social circles that you want to keep in contact with. The
relevant information here is:

1. Who is it?
2. What times of day are you interested in hanging out?
3. How often do you want to see them?
4. Potentially a weighting of key people in the group of overall.

## The event store

Once we have the people who you want to hang out with, we need a
source of truth. Ideally, this would be updated automatically.

My first thought here was that you could just type named people in an
ICAL entry, but it seems that you can't invite someone by name
only. You have to actually send them the invite.

What other sources of truth can we use to determine if you were with
someone other than a manual entry at time of tool use?
