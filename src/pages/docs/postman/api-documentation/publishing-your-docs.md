---
title: "Publishing your docs"
order: 123
page_id: "publishing_your_docs"
contextual_links:
  - type: section
    name: "Prerequisites"
  - type: link
    name: "Intro to collections"
    url: "/docs/postman/collections/intro-to-collections/"
  - type: section
    name: "Additional Resources"
  - type: subtitle
    name: "Case Studies"
  - type: link
    name: "Imgur"
    url: "https://www.postman.com/resources/case-studies/imgur/"
  - type: subtitle
    name: "Videos"
  - type: link
    name: "API documentation with Postman"
    url: "https://www.youtube.com/watch?v=Ayo_KdLLcTA"
  - type: subtitle
    name: "Related Blog Posts"
  - type: link
    name: "API Network Exploration: Infermedica"
    url: "https://blog.postman.com/2018/05/25/api-network-exploration-infermedica/"
  - type: section
    name: "Next Steps"
  - type: link
    name: "Public API documentation"
    url: "/docs/postman-for-publishers/public-api-docs/"

warning: false
---

You can publish your API documentation to make it available for public viewing by anyone who has the link. [Published documentation](/docs/postman-for-publishers/public-api-docs/) allows anyone who wants to learn how to use your API to view detail on endpoints, including parameters, request and response bodies, and example code.

Your public documentation will always display up-to-date content representing the current state of your collection. You don’t need to repeat the publication flow each time you want to update your documentation.

> You can publish documentation for collections that you created or have permission to edit.

## Contents

* [Making your documentation public](#making-your-documentation-public)
    * [Configuring your public docs](#configuring-your-public-docs)
    * [Customizing your docs](#customizing-your-docs)
* [Sharing your public docs](#sharing-your-public-docs)
* [Publishing and unpublishing](#publishing-and-unpublishing)
* [Next steps](#next-steps)

## Making your documentation public

You can publish docs from an existing private documentation page or from the collection in the Postman app.

To publish from your collection's [private documentation](/docs/postman/api-documentation/documenting-your-api/) in the web browser, select a version and click __Publish__.

![Publish Docs](https://assets.postman.com/postman-docs/publish-docs.jpg)

To publish from the collection in the Postman app, select the collection in __Collections__, open the actions menu (__...__), and choose __Publish Docs__.

![Publish Docs](https://assets.postman.com/postman-docs/publish-collection.jpg)

> Any confidential information in your environment, such as __passwords and access tokens__ may become publicly visible when you publish your docs. Remove all sensitive information from the environment before you publish.

### Configuring your public docs

In the __Publish Collection__ page, you can configure how you want your public docs to appear.

* Select a collection [version](/docs/postman/api-documentation/documenting-your-api/#versioning-your-docs) to publish.
* Select an [environment](/docs/postman/api-documentation/documenting-your-api/#documentation-environments) to populate variables in your published documentation.

![Publish Config](https://assets.postman.com/postman-docs/publish-config.jpg)

You can preview your documentation before publishing it. This opens a live preview of the documentation in another window which reloads on any change.

In this live preview, Postman scans the documentation for anything that appears to be a sensitive token. If Postman identifies a potential secret, you will see a banner at the top of this window. Postman will also highlight identified secrets throughout the page. This gives you the chance to update the documentation before publishing it.

![Preview secrets](https://assets.postman.com/postman-docs/client-scanner.png)

### Customizing your docs

> With Postman Team, Business, or Enterprise, you can opt to use a [custom domain](/docs/postman/api-documentation/custom-doc-domains/) for your public documentation site.

You can configure the style of your public docs by selecting colors for the header background, code background, and highlights. You can also choose single or double column view as the default layout for your docs. Try making changes and preview to see how your docs will appear when published.

![Style Docs](https://assets.postman.com/postman-docs/Customizing+public+docs+layout.jpg)

You can customize the style of your public docs by adding a team name and logo via your [team settings](https://go.postman.co/settings/team/general) if you have admin access. Your logo will replace the Postman logo in your team's published docs—updated logo images may take a few minutes to appear.

> You can make changes to styling after publishing your docs by heading to the [Postman Dashboard](https://go.postman.co/workspaces) and navigating to your published collection. Select **Published** in the upper-right corner > **Edit Published Documentation** > **Edit settings**. Make your desired changes and click **Save and republish collection** to update.

## Sharing your public docs

To share your API documentation with your users and the wider Postman community, enable __Collection discovery__ by toggling the switch.

![Collection Discovery](https://assets.postman.com/postman-docs/discovery-switch-template.jpg)

* Choose __Add to API Network__ to [feature your docs in the Postman publisher network](/docs/postman-for-publishers/api-network/add-api-network/).
* Choose __Add to Postman Templates__ to [share your collection with the Postman community](/docs/postman-for-publishers/postman-templates/add-templates/) and make it discoverable via the app.

You can only add to API Network when publishing from a team. You can configure your team profile by clicking __Public Profile Settings__, enabling your profile, and filling out your team details for display.

<img alt="Publish as Team" src="https://assets.postman.com/postman-docs/publish-team.jpg" width="500px"/>

![Enable Profile](https://assets.postman.com/postman-docs/enable-profile.jpg)

Your team profile can include a name, description, custom URL, and logo.

![Profile Detail](https://assets.postman.com/postman-docs/profile-detail.jpg)

Add listing details for your public documentation, including name, summary, description, and relevant tags.

![Listing Detail](https://assets.postman.com/postman-docs/listing-detail.jpg)

If you do not want to make your docs discoverable at this time, you can go ahead and publish then [add them to the API Network or Postman Templates later](/docs/postman-for-publishers/public-api-docs/).

## Publishing and unpublishing

Once you have your publish settings complete, click __Publish Collection__ to make your docs public.

![Publish Docs](https://assets.postman.com/postman-docs/publish-button.jpg)

You will see a confirmation that your docs are public together with a link you can share.

![Docs Published](https://assets.postman.com/postman-docs/docs-published.jpg)

You can unpublish your docs at any time by clicking __Unpublish__.

![Unpublish Docs](https://assets.postman.com/postman-docs/unpublish-docs.jpg)

## Next steps

Find out more about sharing your docs via the [API Network](/docs/postman-for-publishers/api-network/add-api-network/) and [Templates](/docs/postman-for-publishers/postman-templates/add-templates/).
