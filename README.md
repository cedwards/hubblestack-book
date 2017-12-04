# Book Title (working title)
HubbleStack: Open-Source Security Monitoring

## Book Description
HubbleStack uses a powerful framework that allows today's biggest
enterprises to manage tens and even hundreds-of-thousands of servers. Focusing
on ability to scale, flexibility and transparency, HubbleStack has quickly become
the tool of choice for many IT professionals. With this book you will learn how
to leverage HubbleStack to better define, understand and actively monitor your
IT security.

In this book you will learn the motivation for and history behind the project.
You'll find step-by-step instructions on installation and examples of running
your first commands. You'll also learn about extending Hubble for individual
use cases. From there you will explore the main components of Hubble and learn
how to compare your systems against industry best practices. Finally, you will
discover some of the specific lenses HubbleStack uses to view the digital
universe. We'll finish by exploring how to get involved with HubbleStack and
what's happening in the HubbleStack community.

Finally, by the end of this book, you will be able to audit your systems, take
snapshots of system activity, watch for real-time security events and
detail everything using a flexible and modular reporting engine.

## What You Will Learn
1. The real-world motivations for creating Hubble
1. Steps to install Hubble on your servers
1. How to schedule and execute on-demand audits on every one of your systems
1. More clearly define your security policy and use Hubble to monitor it
1. Create human-readable, revision-controlled security profiles
1. Monitor physical or virtual servers in public and private clouds
1. Extend Hubble to handle unique use-cases
1. Leverage Hubble's event system to monitor for real-time security events
1. How to write custom queries to glean information about system and network activity
1. Extend the reporting engine to deliver customized critical alerts

## Table of Contents
1. Forward
   - (???)
1. Preface
   - [Who Should Read This Book](chapters/01-Preface/a-who-should-read-this-book.md)
   - [Why I Wrote This Book](chapters/01-Preface/b-why-i-wrote-this-book.md)
   - [Navigating This Book](chapters/01-Preface/c-navigating-this-book.md)
   - [Conventions Used In This Book](chapters/01-Preface/d-conventions-used.md)
   - [Online Resources](chapters/01-Preface/e-online-resources.md)
   - [Contact the Author](chapters/01-Preface/f-contact-the-author.md)
   - [Acknowledgments](chapters/01-Preface/g-acknowledgements.md)
1. Introduction
   - [History of HubbleStack](chapters/02-Introduction/a-history-of-hubblestack.md)
   - [Motivation for HubbleStack](chapters/02-Introduction/b-motivation-for-hubblestack.md)
   - [Summary](chapters/02-Irtroduction/z-summary.md)
1. Installation - standalone
   - [Introduction](chapters/03-Installation/a-introduction.md)
   - [RHEL Installation](chapters/03-Installation/a-rhel.md)
   - [Debian Installation](chapters/03-Installation/a-debian.md)
   - [Windows Installation](chapters/03-Installation/d-windows.md)
   - [Summary](chapters/03-Installation/z-summary.md)
1. Installation - SaltStack-addon
   - [Introduction](chapters/04-SaltStack-addon/a-introduction.md)
   - [HubbleStack via GitFS](chapters/04-SaltStack-addon/b-installation.md)
   - [Scheduling](chapters/04-SaltStack-addon/c-scheduling.md)
   - [Reporting](chapters/04-SaltStack-addon/d-reporting.md)
   - [Summary](chapters/04-SaltStack-addon/z-summary.md)
1. Optics
   - [Introduction](chapters/05-Optics/a-introduction.md)
   - [What Can Hubble See?](chapters/05-Optics/b-overview.md)
   - [Summary](chapters/05-Optics/z-summary.md)
1. Nova - Hubble's Auditing Engine
   - [Introduction](chapters/06-Nova/a-introduction.md)
   - [Security Profiles](chapters/06-Nova/b-profiles.md)
   - [Security Modules](chapters/06-Nova/c-modules.md)
   - [Nova Utilities](chapters/06-Nova/d-utilities.md)
   - [Extending Nova modules](chapters/06-Nova/e-extending.md)
   - [Summary](chapters/06-Nova/z-summary.md)
1. Nebula - Hubble's Insight Database
   - [Introduction](chapters/07-Nebula/a-introduction.md)
   - [osquery](chapters/07-Nebula/b-osquery.md)
   - [Extending Nebula](chapters/07-Nebula/extending.md)
   - [Summary](chapters/07-Nebula/z-summary.md)
1. Pulsar - Hubble's Event System
   - [Introduction](chapters/08-Pulsar/a-introduction.md)
   - [File Integrity Monitoring](chapters/08-Pulsar/fim.md)
   - [Extending Pulsar](chapters/08-Pulsar/extending.md)
   - [Summary](chapters/08-Pulsar/z-summary.md)
1. Quasar - Hubble's Reporting Network
   - [Introduction](chapters/09-Quasar/a-introduction.md)
   - [Reporting to Logstash](chapters/09-Quasar/b-logstash.md)
   - [Reporting to Splunk](chapters/09-Quasar/c-splunk.md)
   - [Reporting to Slack](chapters/09-Quasar/d-slack.md)
   - [Extending Quasar](chapters/09-Quasar/e-extending.md)
   - [Summary](chapters/09-Quasar/z-summary.md)
1. Configuration & Management
   - [Introduction](chapters/10-Management/a-introduction.md)
   - [Managing Profiles with Revision Control](chapters/10-Management/b-managing-files-with-revision-control.md)
   - [Adjusting the Scheduler](chapters/10-Management/c-adjusting-the-schedule.md)
   - [Extending Reports](chapters/10-Management/d-extending-reports.md)
   - [Maintaining the Fleet](chapters/10-Management/e-maintaining-the-fleet.md)
   - [Performance Tuning](chapters/10-Management/f-performance.md)
   - [Summary](chapters/10-Management/z-summary.md)
1. Get Involved
   - [Introduction](chapters/11-Get-Involved/a-introduction.md)
   - [Contributing Security Profiles](chapters/11-Get-Involved/b-contributing-security-profiles.md)
   - [Contributing Security Modules](chapters/11-Get-Involved/c-contributing-security-modules.md)
   - [Advocating for Better Security](chapters/11-Get-Involved/d-advocating-for-better-security.md)
   - [Summary](chapters/11-Get-Involved/z-summary.md)
