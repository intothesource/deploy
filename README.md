# intothesource/deploy

Deploy helper without an interesting name

## Background

CI/CD helper for deploying PHP (Laravel) applications. Into the Source manages deployments for many different types of hosting platforms, where FTP seems to be the lowest common denominator. Some hosts also support SSH, but the fact that it is not available in some cases poses some challenges.

The aim for this project is to offer tools to tackle these challenges to provide a robust solution for deploying applications.

Tasks (in order)

1. Prepare
2. Lint
3. Build
4. Test
5. Backup
6. Deploy
7. Migrate
8. Rollback

## Solution

This repo provides tasks runners for all of the above. These are designed to be integrated with Gitlab CI/CD. But, rather than relying only on Gitlab CI/CD, this project provides a more standardized solution that should be easier to standardize over many projects.
