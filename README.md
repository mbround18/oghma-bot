# oghma-bot

## DISCLAIMER

This project is on hold, my desktops graphics card is having issues and i dont have the funds for a new one at this time. 

## Info

Bot for D&amp;D to aid in some trivial tasks that can be tedious at the start of the session

[![Build](https://github.com/mbround18/oghma-bot/actions/workflows/build.yml/badge.svg)](https://github.com/mbround18/oghma-bot/actions/workflows/build.yml)

## Current Features

> More can be added, i just want to get this content added initially.
> Will check when completed.

- [ ] Nickname Manager
- [ ] Roll Tables
- [ ] Cleaned up query interface

## Architecture

- Dgraph for the backend, this both is good for singleton and at scale.
- Kubernetes for personal deployment but guide for docker-compose
- Bot access to backend. (command base first to get it working and accessible. BE & FE for mobile/desktop management)
- Backend APi with discord auth checks.
- Frontend for easy management.
