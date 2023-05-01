# Marketplace Partner Apps

This organization contains the source code for partner apps on the [marketplace](https://www.contentful.com/marketplace/) and helpful resources to build your own apps for Contentful.

## Installing an app

Head over to the [marketplace](https://www.contentful.com/marketplace/) and follow the installation flow to set up any of the apps in your Contentful space.

## Adding and maintaining your app in this organization

### First time setup

> **Please note that dependabot is enabled in this repo and will run automatically.**
> While it will attempt to only upgrade dependencies without breaking changes, it is possible it will still introduce issues. Creating and maintaining comprehensive tests is critical to preventing code and build issues.

### Committing and updating your repo

When you are ready to submit your app to the [marketplace apps repo](https://github.com/contentful/marketplace-partner-apps), clone the repo locally, create a new branch with a descriptive name for the app/changes you are introducing, and create a pull-request against the `main` branch. An ecosystems integrations will review your PR soon and let you know if any changes or clarifications are needed. To ensure the fastest approval time on your PR, make sure you:

- Fill out the pull-request template as much as possible. Screenshots, images, and videos are often helpful for providing context and are encouraged.
- Comment your changes, either in GitHub or the code itself to provide reviewers more context than they might get otherwise.
- Ensure your changes are wholly contained within your app's folder, and do not make alterations to other folders or the root level. If you have need for root-level changes, please create an issue instead.
- Prevent / reduce references to external resources and code. The `marketplace-partner-apps` is intended to be open and transparent and any external resources will be _highly_ scrutinized.

## Building your own app

The best way to get started on app development is with our [create-contentful-app](https://github.com/contentful/create-contentful-app) CLI tool.
This tool will bootstrap a brand new project with all the boilerplate code you need to start building an app.
If you are interested in learning how to build a simple example app, you can check out our [tutorial](https://www.contentful.com/developers/docs/extensibility/apps/building-apps/).

Detailed documentation can be found in the [App SDK documentation](https://www.contentful.com/developers/docs/extensibility/ui-extensions/sdk-reference/) and the [Management HTTP API reference documentation](https://www.contentful.com/developers/docs/references/content-management-api/).

Please note that each app has its individual source code license associated with it. Refer to the LICENSE file in the apps root folder.

## Resources

- [Tutorial: Building your first app](https://www.contentful.com/developers/docs/extensibility/apps/building-apps/)
- [Webinar: How to build your first app with Contentful’s new App Framework](https://www.contentful.com/resources/build-app-contentful-app-framework-webinar/)
- [App SDK documentation](https://www.contentful.com/developers/docs/extensibility/ui-extensions/sdk-reference/)
- [Management HTTP API reference documentation](https://www.contentful.com/developers/docs/references/content-management-api/)
- [Marketplace](https://www.contentful.com/marketplace/)
- [App documentation](https://www.contentful.com/developers/docs/extensibility/apps/)
- [Contentful Changelog](https://www.contentful.com/developers/changelog/)
- [Forma 36: The Contentful Design System](https://f36.contentful.com/)

## Support and feature requests

If you require support, or want to request a new feature then please
use the appropriate support channel which will be listed with the app on our [app
marketplace](https://www.contentful.com/marketplace/).
