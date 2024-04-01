# Hypothesis-Testing-Using-Python

Problem Statement:

Many websites offer Light and Dark Theme options, but it's unclear which theme leads to better user engagement and website performance. To address this, I conducted A/B testing to compare user interaction with a Light Theme and a Dark Theme. By analyzing user behavior metrics, I aimed to identify a theme that fosters a more positive user experience and potentially improves conversion rates and other website goals.

Methodology:

I focused on four key user behavior metrics that can indicate user engagement and website effectiveness:

- Click-Through Rate (CTR): Measures how often users click on elements (e.g., buttons, links) after viewing them. A higher CTR suggests users find the elements visually appealing and easy to interact with.

- Conversion Rate: Represents the percentage of visitors who complete a desired action (e.g., purchase, sign-up) after interacting with the website. This is a crucial metric for businesses that rely on online transactions.

- Bounce Rate: Indicates the percentage of visitors who leave the website after viewing only one page. A high bounce rate can suggest users are not finding the information they need or are not engaged by the website's design.

- Scroll Depth: Measures how far down a webpage a user scrolls. Higher scroll depth typically indicates users are interested in the content and are more likely to engage further.

We employed a two-sample t-test, a statistical technique, to compare the means (average values) of these metrics for users who interacted with the Light Theme and those who interacted with the Dark Theme. This allowed us to determine if there were statistically significant differences in user behavior between the two themes.

Result:

![hypothesis](https://github.com/udaisharma99/Hypothesis-Testing-Using-Python/assets/138836370/8d045095-c96e-4c4f-96e0-41efbb4b3825)


Conclusion:

The analysis revealed the following insights:

- Users are more likely to click on elements presented in the Dark Theme, as evidenced by the statistically significant difference in CTR (p-value = 0.048). This suggests the Dark Theme might be more visually appealing or encourage users to interact with calls to action.

- There were no statistically significant differences in Conversion Rate, Bounce Rate, or Scroll Depth between the Light and Dark Themes. This implies that user behavior regarding completing desired actions, leaving the webpage quickly, and scrolling through content seems comparable for both themes.

Overall, while the Dark Theme appears to have a slight advantage in terms of encouraging clicks, user behavior for other key performance indicators seems similar for both Light and Dark Themes
