# Edgedancer Labs – App Documents

This repository holds the public legal and support documents for apps
published by edgedancerlabs, such as privacy policies and instructions
for deleting an account.

The apps' source code is kept in separate private repositories. This
repository exists so these documents have a stable, public address that
app stores (such as Google Play) and users can link to.

The documents are published as web pages at **https://edgedancerlabs.github.io/**.

## Apps

| App          | Privacy Policy | Account Deletion |
|--------------|----------------|------------------|
| Nexus Fusion | [Link](https://edgedancerlabs.github.io/apps/nexus-fusion/privacy-policy) | – (no accounts) |
| Deuterium    | [Link](https://edgedancerlabs.github.io/apps/deuterium/privacy-policy) | [Link](https://edgedancerlabs.github.io/apps/deuterium/account-deletion) |

Each document contains an English and a German version.

## Structure

```
apps/<app-name>/index.md            overview page for the app
apps/<app-name>/privacy-policy.md   privacy policy
apps/<app-name>/account-deletion.md how to delete an account (only for apps with accounts)
_templates/                         starting points for new apps (not published)
_config.yml                         GitHub Pages settings
```

**Rule:** the paths of published documents never change, because app
store listings link to them. Edit the content, not the file names.

## Changes

Every document shows the date it was last changed. The full history is in
this repository's commit log.
