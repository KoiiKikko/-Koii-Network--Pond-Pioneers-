# Koii Network Pond Pioneers
task_name: 'Koii Network Pond Pioneers'
author: 'Koii-Kikko'
description: 'Deploy and operate a Koii node on the Koii testnet to help test critical network functionalities like connectivity, transaction processing, and data storage. Earn testnet KOI tokens and potentially unlock unique benefits in the future Koii ecosystem. Your participation is vital for a smooth mainnet launch. Join the Koi Pond Pioneers today!' 
repositoryUrl: 'https://github.com/KoiiKikko/KoiiKikko/tree/main' #https://www.koii.network/docs/run-a-node/introduction/types-of-nodes
imageUrl: https://www.canva.com/design/DAGR7XQUDEA/7dIY-1awXwk3uwXY7bbaXg/view?utm_content=DAGR7XQUDEA&utm_campaign=designshare&utm_medium=link&utm_source=editor
infoUrl: 'https://koii.network/'

# Task executable network
task_executable_network: 'IPFS'

# Task audit program 
task_audit_program: 'dist/main.js' 

# Round time, audit window, submission window
round_time: 2000 # Increased for potential longer testing durations
audit_window: 700 
submission_window: 700

# Minimum stake amount and task bounty type
minimum_stake_amount: 1.0
task_type: 'KLP'# Koii Network Pond Pioneers

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Building the Koii Network, one node at a time.**

Koii Network Pond Pioneers is a vibrant community of node runners dedicated to supporting and growing the Koii Network. We believe in the power of decentralized networks and are committed to contributing our resources to ensure the network's success.

## Our Mission

* **Run Nodes:** Operate and maintain Koii Network nodes to strengthen the network's infrastructure.
* **Educate:** Share knowledge and expertise about running Koii nodes, helping others get started.
* **Collaborate:** Foster a supportive environment for node runners to connect, exchange ideas, and troubleshoot issues.
* **Advocate:** Promote the benefits of the Koii Network and encourage wider adoption.

## Get Involved

Whether you're a seasoned node runner or new to the Koii Network, we welcome your participation:

* **Join our community:** Connect with other node runners, share your experiences, and learn from the community.
* **Set up a node:** Follow our guides and tutorials to get your Koii node up and running.
* **Contribute to discussions:** Participate in forums and chat channels to exchange ideas and solve problems.
* **Spread the word:** Share information about Koii Network and the Pond Pioneers community with others.

## Resources

* **Node Setup Guides:** Step-by-step instructions for setting up and configuring Koii nodes.
* **Troubleshooting Forum:** A dedicated space for discussing and resolving technical issues.
* **Community Chat:** Connect with other node runners in real-time.
* **Koii Network Documentation:** Official resources and information about the Koii Network.

## Contact Us

We're always happy to hear from fellow node runners and Koii enthusiasts!

* **Email:** [pondpioneers@email.com](koiikikko@gmail.com)
* **Website:** [www.koiinetworkpondpioneers.org](https://www.koiinetworkpondpioneers.org)
* **Social Media:** Follow us on https://www.facebook.com/groups/933863151789100 [Discord](https://discord.gg/koiipondpioneers).

**Together, we can build a stronger, more resilient Koii Network.**

**#KoiiNetwork #PondPioneers #NodeRunners #Decentralization**

# Token Mint Address: (ONLY task_type == KPL) Fire Token as an example here. 
token_type: 5WWwTwzaM9So2pxAY3wzktTDHARhhnRmSvYpxxw5wLkJ


# Total bounty amount and bounty per round
total_bounty_amount: 20 # Increased to incentivize participation
bounty_amount_per_round: 0.2

# Allowed failed distributions and space
allowed_failed_distributions: 3
space: 1 # Increased for potential additional task data

# Hardware requirements (adjust based on actual Koii node requirements)
requirementsTags:
  - type: CPU
    value: '4-core'
  - type: RAM
    value: '8 GB' 
  - type: STORAGE
    value: '10 GB' 

# Task ID and migration description (leave blank for new tasks)
task_id: 'BXbYKFdXZhQgEaMFbeShaisQBYG1FD4MiSf9gg4n6mVn'
