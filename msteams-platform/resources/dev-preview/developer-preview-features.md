---
title: Features in the Public Developer Preview
description: Describes the features in the Public Developer Preview of Microsoft Teams
keywords: teams preview developer features
---

# Features in the Public Developer Preview for Microsoft Teams

The developer preview includes the following new features:

## Tabs Single Sign-On

You can now use [single sign-on (SSO)](~/tabs/how-to/authentication/auth-aad-sso.md) to login and authenticate a user on desktop and mobile using the Teams JavaScript SDK from a web content page. One of the benefits is that a user never has to sign-in; and once they've consented to the app using their profile: they will automatically be signed-in to their tab (including mobile).

Our developer preview is available in manifest versions 1.5 and greater. Our current implementation can only get a limited amount of Graph APIs, however we provide a workaround to get additional Graph APIs using our existing authentication API.

## Personal apps (static tabs and 1-1 bots) enabled on mobile

Installed personal apps (static tabs and 1-1 bots) are now available in the app tray on mobile devices. See [Design guidelines for mobile](~/tabs/design/tabs-mobile.md) for design guidance. Apps can only be installed from a desktop or web client, and can take up to 4 hours to be available on mobile after installation.

This includes the ability for a system administrator to pre-pin an app via [app setup policies](/microsoftteams/teams-app-setup-policies). Apps that have pinned will be displayed in the app drawer.

## Calls and online meeting bots

With the addition of [Microsoft Graph APIs for calls and online meetings](/graph/api/resources/calls-api-overview), Microsoft Teams apps can now interact with users in rich ways using voice and video. These APIs allow you to add new app features such as interactive voice response (IVR), call control, and access to real-time audio and/or video streams for calls and meetings, including desktop and app sharing.

We've added a new section on how to create and develop calls and online meetings bots, starting with the [overview](~/bots/calls-and-meetings/calls-meetings-bots-overview.md).
