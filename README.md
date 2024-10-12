# Premierstacks Public Preview

**This file has been extracted from: [https://github.com/premierstacks/phpstan-stack](https://github.com/premierstacks/phpstan-stack)**

Premierstacks is a collection of proprietary stacks and templates for PHP, JavaScript, TypeScript, React, and Laravel. Because these repositories are private and accessible only through a valid license, we offer this public preview to provide transparency and allow potential users to review the content before making a purchase.

By extracting key documentation and selected sample files to public repositories, we ensure that you can evaluate the quality, structure, and approach of Premierstacks without needing full access. This way, you can make an informed decision about whether our solutions are the right fit for your projects.

To access the complete repositories, along with continuous updates and premium support, a valid Premierstacks license is required.

**Purchase a license here: [GitHub Sponsors](https://github.com/sponsors/tomchochola).**

---

**Original content starts here!**

---

# [PHPStan Stack](https://github.com/premierstacks/phpstan-stack) by [Tomáš Chochola](https://github.com/tomchochola)

✨ _**Clone and Win!**_

The PHPStan Stack is a pre-configured collection of PHPStan setups designed to streamline static analysis for PHP projects. It provides ready-to-use configurations that enforce strict type safety and coding standards, allowing you to focus on building features instead of resolving analysis errors.

## What is PHPStan Stack?

The PHPStan Stack is part of the Premierstacks collection and serves as a robust solution for performing static analysis in PHP projects. It simplifies the integration of PHPStan into various project environments by offering pre-configured setups that cater to different coding styles and frameworks, such as Laravel or pure PHP.

This stack eliminates the common challenges developers face when manually configuring PHPStan, such as handling dependencies, setting up rules, and managing exclusions. By providing a structured configuration out-of-the-box, it ensures consistent coding standards across projects, reducing the time spent on manual setup and minimizing errors related to misconfiguration.

With the PHPStan Stack, you can quickly incorporate static analysis into your workflow and enforce strict type safety without the usual hassle. It allows you to choose between recommended configurations or more advanced setups tailored specifically for complex projects. The stack is designed to be flexible and adaptable, making it a perfect choice whether you’re working on a simple PHP project or a complex application that requires strict code analysis and validation.

## What is Tomchochola

[https://github.com/tomchochola](https://github.com/tomchochola)

This is my personal GitHub profile, where you’ll find public documentation and sample repositories for proprietary packages and templates from Premierstacks. These public repositories are designed to give you an overview of the best practices and high-quality code I follow in all my projects.

## What is Premierstacks

[https://github.com/premierstacks](https://github.com/premierstacks)

Premierstacks is a collection of exclusive, proprietary stacks and templates for PHP, JavaScript, TypeScript, React, and Laravel. It was created to address the common pain points developers face with many open-source projects—quality, consistency, and maintainability. With Premierstacks, you get high-quality tools built with strict attention to detail, designed to help you build and maintain better projects, faster.

## Why Premierstacks?

I created Premierstacks because I wasn’t satisfied with the quality of many open-source projects. Maintaining high-quality code and ensuring long-term reliability is challenging when you’re not earning from the product. When you pay for something, it means the creator truly cares about its success and is committed to delivering the best possible outcome.

Like Apple’s approach with their closed ecosystem, I believe that true excellence can only be achieved when every detail is under your control. That’s why Premierstacks is proprietary software—it's not just about providing solutions; it’s about ensuring those solutions meet the highest standards.

### Why You Should Choose Premierstacks

**🚀 Unmatched Quality**

Our solutions adhere to the highest standards, ensuring clean and maintainable code.

**⚙️ No Setup Hassles**

Pre-configured environments let you start coding immediately—no more complex setups.

**📦 Reuse Across Projects**

Each library and template is built to be reusable, reducing long-term maintenance.

**🔒 Exclusive Resources**

Premierstacks offers tools you won’t find in typical open-source collections.

**🛠️ Always Up-to-Date**

Receive continuous updates and new features, keeping your projects current.

**💪 Expert Creators**

Developed by experienced professionals dedicated to quality and excellence.

## License

**© 2024–Present Tomáš Chochola <chocholatom1997@gmail.com>. All rights reserved.**

This software is proprietary and licensed under specific terms set by its owner.<br />
Any form of access, use, or distribution requires a valid and active license.<br />
For full licensing terms, refer to the LICENSE.md file accompanying this software.<br />

**Purchase a license here: [Github Sponsors](https://github.com/sponsors/tomchochola)**

**See full terms here: [/LICENSE.md](/LICENSE.md)**

## Templates

Explore the predefined templates for various configurations in the [/templates](/templates) directory. These templates provide quick-start setups for different environments.

**[/templates/recommended.template](/templates/recommended.template)**<br />
**[/templates/premierstacks.template](/templates/premierstacks.template)**<br />

## Getting Started

**1. Review the documentation and license**

Ensure this package fits your needs and that you agree with the terms.

**2. Obtain a license**

**Purchase a license here: [Github Sponsors](https://github.com/sponsors/tomchochola)**

**3. Install the package**

Setup composer repostory:

```bash
composer config repositories.premierstacks/phpstan-stack git https://github.com/premierstacks/phpstan-stack.git
```

Install using composer:

```bash
composer require --dev premierstacks/phpstan-stack:@dev
```

**4. Select a template**

Choose one of the predefined configuration templates from the [/templates](/templates) directory that best suits your project’s needs.

Use the `cp` command to copy it into your project as `/phpstan.neon`:

```bash
cp ./vendor/premierstacks/phpstan-stack/templates/recommended.template ./phpstan.neon
# or for internal use
cp ./vendor/premierstacks/phpstan-stack/templates/premierstacks.template ./phpstan.neon
```

**5. CLI**

Execute commands:

```bash
# perform static analysis
./venor/bin/phpstan analyse
```

## About the Creator

I'm Tomáš Chochola, a software developer dedicated to creating exclusive, enterprise-grade software solutions. I specialize in building packages and templates for PHP, JavaScript, and TypeScript, tailored to streamline development workflows, enforce best practices, and save you time.

My mission is to develop reusable solutions that enhance code quality, boost productivity, and ensure that projects remain maintainable and scalable over the long term.

### Specializations

**Backend Development:** Expert in PHP and Laravel<br />
**Frontend Development:** Mastery in TypeScript, React, and JavaScript<br />
**DevOps:** Proficient in managing Ubuntu and AWS environments<br />
**Security:** Focused on implementing best practices and enforcing code standards<br />
**Tooling:** Extensive experience with ESLint, Prettier, PHP CS Fixer, Stylelint, and PHPStan<br />
**Reusable Solutions:** Creating templates and configuration stacks for optimized development<br />
**Development Environments:** Fluent in Windows 11 and Ubuntu (WSL2)<br />

## Contact

**📧 Email: <chocholatom1997@gmail.com>**<br />
**💻 Website: [https://premierstacks.com](https://premierstacks.com)**<br />
**👨 GitHub Personal: [https://github.com/tomchochola](https://github.com/tomchochola)**<br />
**🏢 GitHub Organization: [https://github.com/premierstacks](https://github.com/premierstacks)**<br />
**💰 GitHub Sponsors: [https://github.com/sponsors/tomchochola](https://github.com/sponsors/tomchochola)**<br />

## Tree

The following is a breakdown of the folder and file structure within this repository. It provides an overview of how the code is organized and where to find key components.

```bash
.
├── .editorconfig
├── .gitattributes
├── .gitignore
├── .prettierignore
├── AUTHORS.md
├── LICENSE.md
├── Makefile
├── README.md
├── composer.json
├── eslint.config.js
├── package.json
├── prettier.config.js
├── src
│   └── configs
│       ├── premierstacks.neon
│       └── recommended.neon
└── templates
    ├── premierstacks.template
    └── recommended.template

3 directories, 16 files
```
