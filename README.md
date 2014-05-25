# Piovtal Tracker Gerrit hook
This is a simple Gerrit hook for updating Pivotal Tracker with information about what changes are in Gerrit review.

It parses the commit messages from Gerrit and looks for a Pivotal issue in the style of "Accepted: #42".

## Installation
Install it in $GERRIT_HOME/hooks and edit the script to set the variables at the beginning.
