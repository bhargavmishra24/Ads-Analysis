# Ads-Analysis
# GOAL
The goal of this project is to look at a few ad campaigns and analyze their current performance as well as predict their future performance.

# DESCRIPTION
There are running 40 different ad campaigns and want you to help them understand their performance.<br />

Goal of this project is to:<br />
1) If you had to identify the 5 best ad groups, which ones would they be? Which metric did you choose to identify the best ad groups? Why? Explain the pros of your metric as well as the possible cons.<br />
2) For each group, predict how many ads will be shown on Dec, 15 (assume each ad group keeps following its trend).<br />
3) Cluster ads into 3 groups: the ones whose avg_cost_per_click is going up, the ones whose avg_cost_per_click is flat and the ones whose avg_cost_per_click is going down.<br />

# DATA
We have only one table called "ad_table"<br />

"ad_table" - aggregate information about ads.<br />

Columns:<br />
date : all data are aggregated by date<br />
shown : the number of ads shown on a given day all over the web. Impressions are free. That is, companies pay only if a user clicks on the ad, not to show it.<br />
clicked : the number of clicks on the ads. This is what companies pay for. By clicking on the ad, the user is brought to the site<br />
converted : the number of conversions on the site coming from ads. To be counted, a conversion has to happen on the same day as the ad click.<br />
avg_cost_per_click : on an average, how much it cost each of those clicks<br />
total_revenue : how much revenue came from the conversions<br />
ad : we have several different ad groups. This shows which ad group we are considering.<br />
