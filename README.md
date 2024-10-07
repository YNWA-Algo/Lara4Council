## Business Problem:

Lara C is running for Council in Halifax, NS (Zone 9). Her campaign team has compiled a list of over 30 streets, with addresses representing the full population of households within Zone 9. With electronic voting starting in just 48 hours, the team needs to focus their efforts on engaging only with homes that are eligible to vote, rather than canvassing every household.

## Approach:

The campaign team has two key datasets:

    Canvassing Data: Contains over 30 streets and addresses, marked to indicate whether or not each household has been engaged by the team.

    Electoral Data: Pulled from Elections NS for Zone 9, this dataset lists addresses of households that are eligible to vote.

To streamline the process, I took the following steps:

    Data Preparation: For both datasets, I concatenated the street number and name (e.g., "1707 Pryor" becomes "Pryor1707") to create a standardized address format.

    Matching: Using this concatenated format, I compared the values between both datasets. Where there was a match, I marked the corresponding addresses in the canvassing data under a new column titled 'Priority' with the label "Prioritize."
## Result
The result is a filtered list of homes that are eligible to vote, allowing the campaign team to target these specific households more effectively.

Tech Stack and other tools
1.	Minitab statistical software
2.	Manual Data collection – across all operational locations
3.	Excel

