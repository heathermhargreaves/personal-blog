---
title: 'Personalized Customer Communications using Sentiment Analysis'
date: '2022-05-12'
---

The inspiration for this guide was getting a promotional text to buy another pair of shoes after I had just talked to support asking why my purchase was running two weeks behind. The mismatch in the tone of the promotional text urging me to buy another pair after having an awkward conversation with support made me think there was a missed opportunity for the company to get customer feedback.

This guide walks through how to use IBM’s Sentiment API and Segment to personalize an SMS sent with Twilio's messaging API. An IVR built on Twilio Studio Flow captures the user’s sentiment using IBM’s Sentiment API and sends that sentiment to Segment as a Segment Event. If the user’s sentiment is negative, they receive a text asking for feedback on how their experience can be improved. If the user’s sentiment is positive or neutral, they receive an SMS with a coupon for the next purchase.

This guide was originally published on Twilio's blog.

**Original post: [Personalized Customer Communications using Sentiment Analysis](https://www.twilio.com/en-us/blog/personalized-customer-communications-using-sentiment-analysis)**