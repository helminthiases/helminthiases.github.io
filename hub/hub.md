---
layout: default
title: Content, Repositories
nav_order: 2
description: Outlines the purpose of each hub repository
has_children: true
permalink: /hub
custom_css:
- figures
---

# The Soil Transmitted Helminths Project
{: .fs-9 }

The repositories of the *Helminthiases* hub
{: .fs-6 .fw-300 }

<br>

This page outlines the function of each of the hub's repositories.  Remember, the project's underlying data is the World 
Health Organization's <a href="https://espen.afro.who.int/" target="_blank">ESPEN</a> (Expanded Special Project for the 
Elimination of Neglected Tropical Diseases) <i>geohelminths infections survey experiments</i> 
<a href="https://admin.espen.afro.who.int/docs/api" target="_blank">data</a> 
(ref. <a href="https://helminthiases.github.io">Introductory Notes</a>).

<br>

<table>

  <tr>
      <th style="width:13%;text-align: left;">GitHub Repository</th>
      <th style="text-align: left;">Purpose</th>
  </tr>

  <tr>
    <td><a href="https://github.com/helminthiases/infections#notes" target="\_blank">infections</a></td>
    <td>Focuses on site level geohelminths examinations data.  It
      <ul>
      <li>Inspects the delivered ESPEN geohelminths data; JSON objects.</li>
      <li>Structures the data for exploratory analysis & modelling.</li> 
      <li>Identifies equivalent <i>ESPEN geohelminths infections survey experiments</i> site locations.</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td><ul><li><a href="https://github.com/helminthiases/networks" target="\_blank">networks</a></li></ul></td>
    <td>Hosts a vignette that outlines how equivalent ESPEN site locations are determined.</td>
  </tr>

  <tr>
    <td><a href="https://github.com/helminthiases/spatial" target="\_blank">spatial</a></td>
    <td>The focus herein is geographic information processing.  For each site level location of an ESPEN geohelminths infections data set, the code extracts
      <ul>
      <li>WaSH (water, sanitation, and hygiene) variables estimates</li>
      <li>Population density estimates</li>
      <li>Elevation estimates</li>
      </ul>
      from maps, and subsequently integrates the geohelminths examinations & features estimates.
    </td>
  </tr>

  <tr>
    <td><a href="https://github.com/helminthiases/preliminary" target="\_blank">preliminary</a></td>
    <td>
      <ul>
        <li>Missing Data Analysis: A key model development requisite is an understanding of missing data patterns.</li>
        <li>Exploratory data analysis.</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td><a href="https://github.com/helminthiases/modelling" target="\_blank">modelling</a></td>
    <td>
      <ul>
        <li>Preliminary generalised linear mixed modelling</li>
        <li>Binomial geostatistical logistic modelling</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td><a href="https://github.com/helminthiases/helminthiases.github.io" target="\_blank">helminthiases.github.io</a></td>
    <td>Hosts the code, and graphs, of these GitHub pages</td>
  </tr>

  <tr>
    <td><a href="https://github.com/helminthiases/manuscript" target="\_blank">manuscript</a></td>
    <td>The project's thesis.</td>
  </tr>

  <tr>
    <td><a href="https://github.com/helminthiases/.github" target="\_blank">.github</a></td>
    <td>This is a special GitHub repository.  It hosts the hub's profile.  Ignore.</td>
  </tr>

</table>

<br>
<br>
<br>
<br>

