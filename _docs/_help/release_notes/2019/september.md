---
nav_title: September
page_order: 4

page_type: update
description: "This article contains release notes for September 2019."
---

# September 2019

## Braze App within OneLogin

Customers will be able to simply search and select Braze within [OneLogin]({{site.baseurl}}/user_guide/administrative/access_braze/single_sign_on/onelogin/) for SP or IdP Initiated login. This means that customers will not have to add a custom application within OneLogin. As a result, this should pre-populate certain settings like attributes which we have seen come up since launching SAML SSO.

## Rokt Calendar Partnership

[Rokt Calendar]({{site.baseurl}}/partners/additional_channels/calendar/rokt_calendar/) provides Braze customers the ability to align their personalized marketing initiatives and extend personalized content to the end user's calendar. Thus, making it a more seamless experience for the end user and further develops stickiness with our customers' services. Customers will be able to...

- Send a calendar invite via Braze platform to 'save the date' and extend our communication
- Update an existing invite if the contents of the event has changed.

## Passkit Partnership

With [Passkit]({{site.baseurl}}/partners/additional_channels/mobile_wallet/passkit/), Braze customers will be able to expand their customer engagement to mobile wallet. They will be able to personalized wallet campaigns while using Braze's powerful segmentation and orchestrate alongside channels like push, in-app messages, and more.

## Dispatch ID Value Return via Messaging Endpoints

A message's `dispatch_id` will be included in the following Messaging endpoint responses:

- [`/campaigns/trigger/send`]({{site.baseurl}}/api/endpoints/messaging/#sending-messages-via-api-triggered-delivery)
- [`/campaigns/trigger/schedule`]({{site.baseurl}}/api/endpoints/messaging/#create-schedule-endpoint)
- [`/messages/send`]({{site.baseurl}}/api/endpoints/messaging/#sending-messages-immediately-via-api-only)
- [`/messages/schedule`]({{site.baseurl}}/api/endpoints/messaging/#create-schedule-endpoint)
- [`/canvases/trigger/send`]({{site.baseurl}}/api/endpoints/messaging/#canvas)
- [`/canvases/trigger/schedule`]({{site.baseurl}}/api/endpoints/messaging/#api-triggered-canvases)

This way, customers who use transactional messaging can trace the call back through Currents.

## Canvas Changelogs

Did you even wonder more about the details of who is working on a Canvas in your account? Wonder no more! You can now access Canvas Changelogs.

![Canvas Changelogs]({% image_buster /assets/img/canvas-changelogs.gif %})
