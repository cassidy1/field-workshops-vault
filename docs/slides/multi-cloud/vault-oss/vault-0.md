name: vault-title-slide
class: title, shelf, no-footer, fullbleed
background-image: url(https://hashicorp.github.io/field-workshops-assets/assets/bkgs/HashiCorp-Title-bkg.jpeg)
count: false

# Vault Workshop
## Modern Security with Vault for any Cloud

![:scale 15%](https://hashicorp.github.io/field-workshops-assets/assets/logos/logo_vault.png)

???
Welcome to the Vault workshop.

Usually one of the first questions I get is, can I have a copy of the slides? And Yes! You can use this link to follow along which will be available after the workshop. I'll paste a copy of this in the chat.

---
layout: true

.footer[
- Copyright © 2019 HashiCorp
- ![:scale 100%](https://hashicorp.github.io/field-workshops-assets/assets/logos/HashiCorp_Icon_Black.svg)
]

---
name: Link-to-Slide-Deck
# The Slide Deck
<br><br>
### Follow along on your own computer at this link:

https://bit.ly/intuitive-vault-workshop

???

The link to this slide deck

---
name: Introductions
# Introductions

* Name - Ryan Cassidy
* Job Title - Solutions Engineer
* Secrets Management Experience
  * 2 1/2 Years at Hashicorp
  * Vault Subject Matter Expert
  * Prior to HashiCorp I worked in Ad Tech

???
* Use this slide to introduce yourself, give a little bit of your background story, then go around the room and have all your participants introduce themselves.

* The favorite text editor question is a good ice breaker, but perhaps more importantly it gives you an immediate gauge of how technical your users are.

---
name: Table-of-Contents
# Table of Contents

1. HashiCorp Vault Overview
1. Interacting with Vault
1. Running a Production Server
1. Vault Secrets Engines
1. Vault Authentication Methods
1. Vault Policies
1. Dynamic Database Secrets
1. SSH Secrets Engine
1. Encryption as a Service

???
* We will start out with an overview of Hashicorp Vault
* Vault Basics
* Different ways to Authenticate
* Store and Get Secrets
* Find out what Dynamic Secrets Are?
* In our final lab we will setup Encryption as a Service

---
name: instruqt-tracks
# Lab Environment Used
* This workshop uses [Instruqt](https://instruqt.com) for hands-on labs.
* Instruqt labs are run in "tracks" that are divided into "challenges".
* This workshop uses the following tracks:
    1. [Vault Basics](https://play.instruqt.com/hashicorp/invite/qfwncq62zsxu)
    1. [Vault Dynamic Database Credentials](https://play.instruqt.com/hashicorp/invite/sryhqfdm6sgx)
    1. [Vault Encryption as a Service](https://play.instruqt.com/hashicorp/invite/qleasfx1dszc)
* We'll cover chapters 1-6 and then do the first lab.
* We'll then cover chapter 7 with the second lab.
* We'll finish with chapter 8 and the third lab.
