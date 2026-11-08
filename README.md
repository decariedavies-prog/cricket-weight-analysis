# Cricket body size, diet and calling energy (R)

A university data science project, analysed in R, on the cricket *Gryllodes sigillatus*. The full report is in this repository: `data_science_resubmision.pdf`.

## The question
Do a cricket's size, mass and diet relate to how much energy it uses when producing sound (its calling song)? Calling is how males attract females, so the aim was to see whether body size could help explain calling effort.

## What I did
- Cleaned the data and plotted diet, size, mass and energy used when producing sound in R, with fitted trend lines and colour to show a third variable.
- Tested the relationships with linear regression, ANOVA and a Mann-Whitney U test.
- Compared my results with published research on cricket calling behaviour.

## What I found
- **Diet and mass:** no significant relationship (p = 0.92).
- **Diet and size:** no significant relationship (p = 0.80).
- **Body size and energy used to produce sound:** a significant positive relationship (p < 0.001, ANOVA F = 26.4), so larger crickets used more energy when calling.

## What I would do differently
- Use clearer charts. My first chart is a line graph with a lot of overlapping lines, and a scatter plot or box plot would show the diet and size data more honestly.
- Check each test's assumptions properly before choosing it, and explain the results in plainer language.
- Rebuild the analysis in Python as I learn it, to compare approaches.

## Notes
- Tools: R, ggplot-style charts, basic statistical testing.
- The dataset came from my university module and is not included here.
- Created as part of my BSc Biological Sciences at the University of East Anglia (2023).

Contact: Decarie321@gmail.com
