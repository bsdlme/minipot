# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0] 2019-12-10
### Added
README: quickstart guide
pot: add initialization steps
traefik: proxy configuration file
newsyslogd: log rotation for traefik
cron: pot prune cron job (every 15 minutes)
minipot-start.sh: easy script that start all the needed services

### Changed
minipot scripts: remove .sh suffix
consul: agent bind to 0.0.0.0
nomad: small naming improvements
minipot-init.sh: renamed from bootstrap.sh
Provide the IP is not mandatory anymore

## [0.0.1] 2019-11-13
### Added
consul: agent configuration file
nomad: server configuration file
syslogd: configuration files
newsyslogd: log rotation configuration files
bootstrap.sh: script with additional conifguration and preparation
example: add a job example
