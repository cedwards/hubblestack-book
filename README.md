# Book Title (working title)
HubbleStack: Open-Source Security Monitoring

## Book Description
HubbleStack was designed using a powerful framework that allows today's biggest
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
report all of this using a flexible and modular reporting engine.

## What You Will Learn
1. The real-world motivations for creating Hubble
1. Steps to install Hubble on your servers 
1. How to schedule and execute on-demand audits on all of your systems
1. More clearly define your security policy and use Hubble to monitor it
1. Create human-readable, revision-controlled security profiles
1. Monitor physical or virtual servers in public and private clouds
1. Extend Hubble to handle unique use-cases
1. Leverage Hubble's event system to monitor for real-time security events
1. How to write custom queries to obtain snapshots of system and network activity
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
   - [HubbleStack via GitFS]()
   - [Scheduling]()
   - [Reporting]()
   - [Summary]()
1. Components
   - [Introduction]()
   - [What Can Hubble See?]()
   - [Summary]()
1. Nova - Hubble's Auditing Engine
   - [Introduction]()
   - [Security Profiles]()
   - [Security Modules]()
   - [Nova Utilities]()
   - [Extending Nova modules]()
   - [Summary]()
1. Nebula - Hubble's Insight Database
   - [Introduction]()
   - [osquery]()
   - [Extending Nebula]()
   - [Summary]()
1. Pulsar - Hubble's Event System
   - [Introduction]()
   - [File Integrity Monitoring]()
   - [Extending Pulsar]()
   - [Summary]()
1. Quasar - Hubble's Reporting Network
   - [Introduction]()
   - [Reporting to Logstash]()
   - [Reporting to Splunk]()
   - [Reporting to Slack]()
   - [Extending Quasar]()
   - [Summary]()
1. Configuration & Management
   - [Introduction]()
   - [Managing Profiles with Revision Control]()
   - [Adjusting the Scheduler]()
   - [Extending Reports]()
   - [Maintaining the Fleet]()
   - [Performance Tuning]()
   - [Summary]()
1. Get Involved
   - [Contributing Security Profiles]()
   - [Contributing Security Modules]()
   - [Advocating for Better Security]()
   - [Summary]()
