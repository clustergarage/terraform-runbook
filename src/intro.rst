Introduction
============

The genesis of this document came out of conversations with HashiCorp `Terraform <https://terraform.io>`_  users and contributors. There are several good examples of building out Terraform Open Source (TF OSS) and scaffolding around it.  This guide builds on that work to deliver a clear and concise set of best-practices to set users and organizations up for success as they mature. 

Objectives
----------

The objectives of this document are to:

1. Define common :ref:`workflows <workflows>` that Terraform Cloud and Enterprise enable
2. Discuss how :ref:`Terraform workspaces <workspaces>` enables these workflows and support long-term adoption from Terraform OSS to TFC or TFE
3. Recommendations and reasoning behind successful :ref:`patterns <patterns>` with HashiCorp Terraform and Version Control
4. :ref:`Anti-patterns <anti-patterns>` and reasoning behind why these may be challenging over time
5. Utilizing Terraform :ref:`modules <modules>` to enable a producer/consumer model
6. Identify what the :ref:`adoption journey <adoption>` looks like and how to set yourself up for success
7. Discuss leveraging :ref:`providers <providers>`, including custom providers and open source providers

We hope this document is useful and appreciate any feedback.
