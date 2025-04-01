| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique and Redesign of Chart: Which social media platforms are most common?

## Step one: the visualization

Link to the original data visualization:
Author, N. (2025, March 31). Social media fact sheet. Pew Research Center. https://www.pewresearch.org/internet/fact-sheet/social-media/?tabItem=3345cffa-94a6-4e74-9272-70dee1e0e213#who-uses-each-social-media-platform/

I selected this social media platform usage visualization because it provides a comprehensive view of how digital social behaviors have evolved over the past decade. The data reveals not just which platforms dominate the landscape (YouTube and Facebook), but also captures the emergence and rapid adoption of newer platforms like TikTok alongside the steady growth of established networks like Instagram. This chart can help us understand how people choose social media across time with different purposes.

## Step two: the critique
Overall, this is an effective visualization that prioritizes clarity and accuracy over flashy design. Thus, it is a solid example of informative data presentation. 
What stood out is the divergent paths of different platforms tell interesting stories. Instagram's consistent growth contrasts with Facebook's stagnation and youtube sudden dominance.

What Worked Well: 
1. Clear visual hierarchy: The chart effectively uses color differentiation to make it easy to track individual platforms across time.
2. Context through scaling: The y-axis starting at 0% and extending to 100% provides appropriate context for comparing relative popularity.

What didn't work well:
1. Overlapping lines in congested areas: The middle section of the chart where several platforms cluster between 20-40% usage which is difficult to track individual platforms precisely.
2. Limited context for shifts: While the chart shows the trends, it doesn't provide context for significant changes.
3. Messy Platform categorization: Some might question whether LinkedIn and WhatsApp are directly comparable to entertainment-focused platforms like YouTube or TikTok, as they serve different purposes.
4. No age group information.

## Step three: Sketch a solution

1. Addressing the "clustering problem" in the 20-40% range where multiple platforms overlap, making it difficult to distinguish individual trends. [Use Split-panel]
2. Adding platform categorization to provide context for why certain platforms behave differently: [Filter by platform category]
Entertainment/Content Consumption (YouTube, TikTok)
Social Networking (Facebook, Instagram)
Professional Networking (LinkedIn)
Messaging/Communication (WhatsApp)
News/Discussion (Reddit, X/Twitter)

## Step four: Test the solution

![image](https://github.com/lily-lee-ops/Jingxuan-Li-portfolio/blob/main/sketch.jpg)

<img src="https://github.com/lily-lee-ops/Jingxuan-Li-portfolio/blob/main/sketch.jpg" width="600"/>

Questions to ask: 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Summary Improvement Results: 

1. Distingush different platform in different colors more clearly.
2. Add some rank information to tell some stories to audience.


Synthesis: 

1. Emphasize the top 3-5 social media that most people used.
2. Change the colors of the lines to show the market share or rank information of each social media.

## Step five: build the solution
1. Split-Panel Approach for Clustering Problem
The main visualization will be divided into two connected panels:
Main Panel: Shows the complete trend lines for all platforms from 0-100%, maintaining the big picture view of the data. This preserves the clear visibility of dominant platforms like YouTube and Facebook.
Focus Panel: A magnified view of just the 20-40% range where multiple platforms cluster together. This expanded section gives these mid-tier platforms room to breathe visually, making individual trend lines for LinkedIn, WhatsApp, Snapchat, X/Twitter, Reddit, etc. much easier to distinguish.

2. Platform Categorization Implementation
Platforms will be organized into meaningful categories and use category filtering controls: Interactive filters that allow users to:
-View all platforms simultaneously
-Focus on a single category (e.g., only Entertainment platforms)
-Compare selected categories side-by-side
-Hide categories not relevant to their analysis

![image](https://github.com/lily-lee-ops/Jingxuan-Li-portfolio/blob/main/Dashboard_m.png)

If you cannot see the picture on website, you can visit this link to see: https://public.tableau.com/app/profile/jingxuan.li4154/viz/MakeoverMon/Dashboard1?publish=yes/

## References
Author, N. (2025, March 31). Social media fact sheet. Pew Research Center. https://www.pewresearch.org/internet/fact-sheet/social-media/?tabItem=3345cffa-94a6-4e74-9272-70dee1e0e213#who-uses-each-social-media-platform
## AI acknowledgements
Use Claude to inspire ways to categorize the social media.
