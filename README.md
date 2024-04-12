# WP Acceptance

> WP Acceptance is a toolkit that empowers developers and CI pipelines to test codebases using version controlled acceptance tests and sharable environments.

[![Support Level](https://img.shields.io/badge/support-archived-red.svg)](#support-level) [![Release Version](https://img.shields.io/github/v/tag/10up/wpacceptance?label=version)](https://github.com/10up/wpacceptance/releases) [![Documentation Status](https://readthedocs.org/projects/wpacceptance/badge/?version=latest)](https://wpacceptance.readthedocs.io/en/latest/?badge=latest) [![MIT License](https://img.shields.io/github/license/10up/wpacceptance.svg)](https://github.com/10up/wpacceptance/blob/master/LICENSE.md)

> [!CAUTION]
> As of 12 April 2024, this project is archived and no longer being actively maintained.

## Requirements

* PHP 7.2+
* [mysqli PHP extension](https://www.php.net/manual/en/book.mysqli.php)
* Docker ([WP Local Docker](https://github.com/10up/wp-local-docker) is highly recommended as the local development environment but not required.)
* Node >= 8 (WP Acceptance uses [Puppeteer](https://pptr.dev/) behind the scenes.)

*Note:* WP Acceptance should be run on your HOST machine and not within Docker.

## How It Works

There are many acceptance tests frameworks out there. They all have one major flaw - everyone executing the acceptance tests must be running the exact same code on the exact same database and environment to guarantee the same results. Ensuring a team of developers (and a CI pipeline) are all using the same database in the same environment has been nearly impossible until now. WP Acceptance is unique in that it allows you to run your acceptance tests against a codebase in defined and shareable environments.  Read more in our [announcement blog post](https://10up.com/blog/2019/introducing-wp-acceptance/).

## Install

Installation instructions are on the [docs site](https://wpacceptance.readthedocs.io/en/latest/#installation).

## Usage

Learn how to use WP Acceptance on the [docs site](https://wpacceptance.readthedocs.io/en/latest/cookbook/).

## Support Level

**Archived:** This project is no longer maintained by 10up. We are no longer responding to Issues or Pull Requests unless they relate to security concerns. We encourage interested developers to fork this project and make it their own!

## Like what you see?

<a href="http://10up.com/contact/"><img src="https://10up.com/uploads/2016/10/10up-Github-Banner.png" width="850"></a>
