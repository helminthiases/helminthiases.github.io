---
layout: default
title: Missing Data Patterns Analysis
parent: ESPEN Data
nav_order: 3
custom_js:
- latex 
custom_css:
- tooltips
- figures
---

# Missing Data Patterns Analysis
{: .no_toc }

<br>

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<br>

---

## Null Regression & Correlation

<p style="margin-top: 20px; margin-bottom: 10px">
Most of the data's variables have missing values.  Prior to deciding how to address missing values, it is important to understand the 
missing values patterns [@steyerberg2010]. Rubin [@rubin1976, @steyerberg2010, @little2019] outlines three fundamental missing data 
mechanisms
</p>

> * Missing Completely at Random (MCAR): administrative errors, accident.
> * Missing at Random (MAR): there's an association between a variable's missing data and available independent variables / outcomes.
> * Missing Not at Random (MNAR): missing data associated with missing values of the factor/predictor in question or with unobserved predictors.

<p style="margin-top: 20px; margin-bottom: 5px">
If the missing values of a data set in question are *missing completely at random* then complete case analysis will suffice 
because the complete case excerpt is akin to a random sample from a complete population.  If MCAR does not hold, e.g., 
data is *missing at random*, then the complete case excerpt is not representative of the underlying population, therefore population 
inference is not possible via complete case analysis. [@steyerberg2010]
</p>

The null regression investigates whether the missing values of a reference, i.e., independent, variable are 
predictable.  The hypotheses are

> $$H_{0}$$: The missing values of a reference/independent variable are not predictable via an outcome variable, or 
> by other independent variables.

> $$H_{1}$$: It is quite probable that the missing values of a reference/independent variable are predictable via 
> an outcome variable, or by other independent variables.

<p style="margin-top: 20px; margin-bottom: 5px">
By the generalised linear model set-up
</p>

$$h(.) = \beta_{0} + \beta_{1}*(\textit{ascariasis prevalence}) + \beta_{2}*(\textit{trichuriasis prevalence}) + \ldots $$

The null hypothesis should be rejected in favour of $H_{1}$ if the coefficient $\beta_{i}$ of a variable 
has a $p_{value} < 0.05$.&nbsp; &nbsp; Such a low $p_{value}$ implies that the missing values 
**are not missing completely at random**.

<p style="margin-top: 20px; margin-bottom: 10px">
Within the null regression graphs below a $p_{value}$ is inapplicable, and missing data analysis is 
unnecessary, <b>if the reference variable is not missing any values</b>.  If values are missing the square is black, hover 
over a black square to view the $p_{value}$ <span class="tooltip">w.r.t.<span class="tooltiptext">with respect to</span></span> 
the coefficient of a variable.
</p>

<div class='tableauPlaceholder' id='viz1658092680967' style='position: relative'>
<noscript><a href='#'><img alt='Missing Data ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MissingData_16579829908770&#47;MissingData&#47;1_rss.png' style='border: none' /></a></noscript>
<object class='tableauViz'  style='display:none;'>
<param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
<param name='embed_code_version' value='3' /> 
<param name='site_root' value='' />
<param name='name' value='MissingData_16579829908770&#47;MissingData' />
<param name='tabs' value='no' /><param name='toolbar' value='yes' />
<param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MissingData_16579829908770&#47;MissingData&#47;1.png' /> 
<param name='animate_transition' value='yes' />
<param name='display_static_image' value='yes' />
<param name='display_spinner' value='yes' />
<param name='display_overlay' value='yes' />
<param name='display_count' value='yes' />
<param name='language' value='en-GB' />
<param name='filter' value='publish=yes' />
</object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1658092680967');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='600px';vizElement.style.height='1127px';                    
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

<br>
<br>
<br>
<br>


