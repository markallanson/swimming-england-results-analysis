# Swim England swimming times analysis
This repository contains some prompting that allows [gemini-cli](https://github.com/google-gemini/gemini-cli) to perform analysis of time results from Swim England licensed meets.

It currently only supports individual time analysis by querying for specific swim england members only. There is no support for analysing event specific data not rooted in a Swim England member. 

# Usage
Install gemini-cli, clone the repository, then run `gemini`.

# Example queries

Summarize PBs for a single swimmer (it will ask if it needs help identifying the correct swimmer):

   > Show Adam Peaty's PBs

Drill into details about a specific event (follow-on from the prior query).

   > analyze the progression in 200m free

Compare two swimmers in a specific event

   > compare the results of Adam Peaty and 
 Ross Murdoch in 50m breast

Determine qualifying likelyhood for a single event in a meets

   > analyze this years progression for My Swimmer Name in 100m breast and comment on the likelyhood of qualifying for /future meet name/ based on last years qualifing time requirements


