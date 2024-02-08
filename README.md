# Welcome to the Deploy PHP to Vercel

![Plugin Logo](plugin_logo.png)

👋 Most simple example project is this one, using following project structure.
```
project
├── api
│   └── index.php
└── vercel.json
```
First file api/index.php is entrypoint of our application. It should be placed in api folder, it's very standard location for Vercel.
```
<?php
phpinfo();
```
Second file vercel.json is pure gold here. Setup your project with configuration like this and voila. That's all.
```
{
  "functions": {
    "api/*.php": {
      "runtime": "vercel-php@0.6.0"
    }
  }
}
```
Last thing you have to do is call vercel.


## What is the Deploy PHP to Vercel?

![Plugin Logo](plugin_seo.png)

Get insight into the loading speed, responsiveness, visual stability, and other metrics that contribute to a great end-user experience for your site or application.

## Key Features

- 🚀 **Feature 1:** Accelerate your workflow with a set of intuitive shortcuts and automation tools. Spend less time on repetitive tasks and more time on what truly matters.
- 🎨 **Feature 2:** Seamlessly integrate with your favorite design and development tools. Our plugin plays well with industry standards, ensuring a smooth collaboration between teams.
- 📦 **Feature 3:** Access a library of pre-built templates and modules that can be easily customized to fit your project requirements.
- 📊 **Feature 4:** Gain valuable insights with built-in analytics and performance tracking. Optimize your project's efficiency and make data-driven decisions.
- ⚙️ **Feature 5:** Extensible architecture allows developers to create and share their own plugins and extensions, expanding the capabilities of the XYZ Plugin.

## Getting Started

Getting started with the XYZ Plugin is a breeze:

1. **Installation:** npm i -g vercel.
2. **Activation:** vercel
3. **Exploration:** vercel

## Set up and deploy ?

Yes

## In which directory is your code located?

./

## Want to modify these settings?

No

## Feedback and Support

Discover *.vercel.app/api/ PHP functions

## Contributing

We welcome contributions from the community! If you're interested in improving the XYZ Plugin, please review our [Contribution Guidelines](contributing.md).

## Stay Connected

Stay up-to-date with the latest developments, updates, and announcements by following us on [Twitter](https://twitter.com/xyzplugin) and subscribing to our newsletter on our official website.

We're excited to have you on board and can't wait to see how the XYZ Plugin transforms your creative and development endeavors. Happy coding!

*— The XYZ Plugin Team*
