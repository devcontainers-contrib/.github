<!--
This is an official document. Use AP-style title case for headings. This
document MAY be moved to a CHARTER.md or similar location if a more user-focused
README.md is provided.

The convention is "dev containers" in formal settings, but "devcontainers" in
informal settings. The official specification and documentation use "dev
containers", but most external documents use "devcontainers". Both of these are
nouns, not names, and can as such be capitalized.
-->

# [Community Dev Containers] Charter

The [Community Dev Containers] project aims to document, maintain, and improve
on the official devcontainers images, features, and templates to improve the
developer experience for end-users.

## Guiding Principles

The [Community Dev Containers] project operates under principles similar to
those of the [OpenJS Foundation]. It operates collaboratively, openly,
ethically, and transparently. Project proposals, ideas, timelines, and statuses
should not merely be open and available, but also easily visible to outsiders.
Outside users and developers should be able to participate in discussions,
ideas, issues, and make contributions with as little effort as possible.

## Problem

The current official [@devcontainers] project's scope is limited to features,
images, and templates that serve only the highest level of most popular
programming environments.

For instance, the [devcontainers/features] repository contains only 28 different
addons. The [devcontainers/images] repository only has a selection of 15
different development environment baselines.

This project is the centralized unofficial hub for other features, images, and
templates that would not be permitted to fall under the official
[@devcontainers] umbrella.

## Scope

The [@devcontainers-contrib] organization maintains and evolves the images,
features, templates, and documentation content for aspects not covered by the
official [@devcontainers] organization. It provides a stable, yet flexible, set
of supporting software for users who use dev containers that is governed to
accomodate their desires. This project's value is its balance between
administration and community adherence. It's scope includes listening and
responding to user feedback.

### In-scope

- Docker images for ecosystems not covered an official dev containers image
- Feature collections for popular tools that are typical on developer computers
- Templates for popular project configurations and setups
- Conventions and best-practices to follow architecting a dev container
- Make it easy to propose, add, or otherwise discuss additional features,
  images, and templates

Tutorials and guides on how to use dev containers are not covered under the
umbrella of the [Community Dev Containers] project. These items can be pursued
by individual members, but are not endorsed or covered under this organization's
scope.

### Out-of-Scope

- Creating a dev container feature for every single Node.js or Python package
- Maintaining a dev container image for all permutations of tooling mashups
- Fixing users' broken dev container configurations
- Answering questions about decisions made by the official [@devcontainers]
  organization

[openjs foundation]: https://openjsf.org/
[@devcontainers]: https://github.com/devcontainers
[@devcontainers-contrib]: https://github.com/devcontainers-contrib
[community dev containers]: https://github.com/devcontainers-contrib
[devcontainers/features]: https://github.com/devcontainers/features#readme
[devcontainers/images]: https://github.com/devcontainers/images#readme
