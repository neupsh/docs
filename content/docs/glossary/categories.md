---
layout: page
weight: 0
title: Categories
navigation:
  show: false
seo:
  title: Categories
  override: true
  description: Paying attention to your deliverability metrics can help optimize your delivery rate and reduce the risk of being seen as a spammer.
---

Categories help organize your email analytics by enabling you to tag emails you send by topics you define.

<call-out type="warning">

This information will be stored as a “Not PII” field and may be used for counting or other operations as SendGrid runs its systems. These fields generally cannot be redacted or removed. You should take care not to place PII in this field. SendGrid does not treat this data as PII, and its value may be visible to SendGrid employees, stored long-term, and may continue to be stored after you’ve left SendGrid’s platform.

</call-out>

Just as you can view the statistics on all your activity under the '[Statistics]({{root_url}}/ui/analytics-and-reporting/stats-overview)' tab, you can go a step further and view the [statistics broken down to a particular category]({{root_url}}/ui/analytics-and-reporting/categories/).

The events that can be associated with category include:

- Emails sent
- Clicks
- Emails opened
- Emails bounced
- Spam Reports
- Unsubscribes

The actual statistics included vary depending upon the set of enabled apps. Emails sent, bounces, and spam reports will always get tracked. [Unsubscribes]({{root_url}}/ui/sending-email/subscription-tracking/), [Clicks]({{root_url}}/ui/analytics-and-reporting/click-tracking/), and Opens require that the associated Setting is enabled. Check out [Settings](https://app.sendgrid.com/settings) to see which apps you have enabled.

In order to add the X-SMTPAPI categories header, please look at our [SMTP API Categories]({{root_url}}/for-developers/sending-email/categories/) documentation. You can also get a [full category list]({{root_url}}/for-developers/sending-email/categories#get) or get [category specific statistics]({{root_url}}/API_Reference/Web_API_v3/Stats/categories.html) from the SendGrid API.

<call-out-link linktext="EXPERT INSIGHTS" img="/img/expert-insights-promo2.png" link="https://sendgrid.com/solutions/expert-insights/">

### Looking for more visibility into your email performance?

Send better email with Expert Insights. Our detailed monthly reports will enable you to understand your email reputation and recipient engagement and repair issues with expert how-to steps.

</call-out-link>
