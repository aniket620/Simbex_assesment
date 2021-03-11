# Simbex_assesment
Coding assignment 1 – Develop a program in C to do the following:
Read in a binary file, convert to S-record, and write back out as an S-record.
Read in an S-record file, convert to binary and write back out.
Read a file (S-Record or binary) and send down RS-232 port.
 

Coding assignment 2: Write a program to process attached data and find list of sessions.
Inputs: TestData.xls (Attached csv)
Expected outcome:
Display or write to a file  with a list of sessions.

 

Definitions: A session is defined by begin and end.
Session begin
On a given day, within a 5 min period 15% of players on roster need to have an activity record in that period.
AND at least one player has an HeadImpact record.
Then subtract 10 minutes
 

End of session:
On a given day, within a 5 min period 15% of players on roster need to have activity record in that period.
AND at least one player has an HIE record.
Then if no record meets criteria after 40 minutes, then move back to last valid record and add 40 mins.
