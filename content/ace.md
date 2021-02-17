---
title: "ACE Staff Site"
date: 2021-02-13T21:41:10-05:00
draft: true
---

### ACE

[https://ace.scholarsportal.info](https://ace.scholarsportal.info)

**Roles:**
Frontend development and UX design.

**Technology:**
Drupal 8, PHP, Python

This is the staff site used by ACE coordinators across OCUL and OCLS for submitting and viewing requests, community submissions, and usage data. The public facing side also serves as a learning guide for ACE users. The site features a custom Drupal module for handling request submissions and workflow. Recently, a content submission form was added for community scanned books to be ingested into the ACE repository. A server side Python script harvests data from Drupal and transforms it into a BITS XML file that gets loaded into the Book platform.

{{< gallery caption-position="none" >}}
{{< figure link="/images/ace_home.png" alt="" thumb="-thumb" caption="ACE staff site home page" >}}
{{< figure link="/images/ace_add.png" alt="" thumb="-thumb" caption="The request submission form allows for multiple submissions and performs an ISBN check to see if a scanned copy already exists." >}}
{{< figure link="/images/ace_processing.png" alt="" thumb="-thumb" caption="Requests that are in the \"In Processing\" part of the request workflow. Users can log in to check the status of their requests and are automatically notified when they are ready." >}}
{{< figure link="/images/ace_filesub.png" alt="" thumb="-thumb" caption="The submission form for community submitted content." >}}
{{< /gallery >}}