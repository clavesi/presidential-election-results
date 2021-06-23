# Presidential Election Results

## What is this?

A collection of the results of every US presidential election. For every election, there's a JSON file with the corresponding year as its name. NOTE: popular vote doesn't really show up until 1824.

From the 1788 election to the 1920 election, [The American Presidency Project](https://www.presidency.ucsb.edu/statistics/elections) is used.

From the 1924 election to present, [The Clerk of the House's PDFs](https://history.house.gov/Institution/Election-Statistics/) are used.

## Issues

1) Starting in 1976, the popular votes are the amount that the House PDF give for that specific party. In previous elections, sometimes other parties' votes are added as they picked the Dem. or Rep. candidate too. Almost every source also adds them together, but the House sometimes separates them. Between the 1936 and 1976 election, I sometimes added them and other times didn't. This leads to inconsistent results that will be fixed at some point.
2) In the 2000 election, the popular vote of George W. Bush is summed up wrong on the House's PDF. It's actually 50,456,169 votes while the PDF says 50,465,169 (456 vs 465). I've contacted the House Clerk's office and nothing can be done about it because it's a government record.
3) In certain elections, electors go against their party and cast their own ballot. These are known as faithless electors. In these cases, the person who got the electoral vote is added to the candidates  list but retains a popular vote of 0. If you wish to use this, I'd take care to check when this happens and handle it accordingly, possibly by just grouping them all together.
4) It's likely that I have messed up somewhere since I'm only human and I did this all by hand. I may have put one number in front of another that was supposed to go behind. I've tried to check as much as I could manually and automatically with code, but I'm sure issues still slip through, other than those above.
