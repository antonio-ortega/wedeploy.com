---
title: "Getting Started"
description: "Send emails asynchronously and check their status using WeDeploy™ Email"
headerTitle: "Email"
layout: "guide"
weight: 1
---

### Email

###### {$page.description}

<div class="guide-btn-cta">
	<a class="btn btn-accent btn-sm" href="http://boilerplate-email.wedeploy.io" target="_blank">
		<span class="icon-16-external"></span>See Live Demo
	</a>
</div>

<div class="guide-aux-cta">
	or read the <a href="https://github.com/wedeploy/boilerplate-email/tree/js" target="_blank">source code</a>.
</div>

<article id="1">

## Install dependencies

This section assumes that you already have the **WeDeploy CLI** installed and **Docker** running. Make sure to [visit the installation guide](/docs/intro/using-the-command-line.html) if you need help setting that up.

We also feature code snippets using the API Client, [visit this guide](/docs/intro/using-the-api-client.html) in order to start using it.

</article>

<article id="2">

## Running locally

<ol>

<li>Start local infrastructure:</li>

```xml
we run
```

<li>Clone this repository:</li>

```xml
git clone -b js https://github.com/wedeploy/boilerplate-email.git boilerplate-email-js
cd boilerplate-email-js
```

<li>Link this container with the local infrastructure:</li>

```xml
we link
```

<li>Now your container is ready to be used:</li>

```xml
http://emaildemo.wedeploy.me
```

</ol>

</article>

<article id="3">

## Deploying to the cloud

<ol>

<li><a href="https://github.com/wedeploy/boilerplate-email/fork">Fork this repository</a>.</li>
<li>Go to the <a href="http://dashboard.wedeploy.com">Dashboard</a>.</li>
<li><a href="http://dashboard.wedeploy.com/projects/create">Create a project</a>.</li>
<li>In the sidebar, click on <strong>Deployment</strong>.</li>
<li>Using your local machine, clone your Github fork:</li>

```xml
git clone https://github.com/<username>/boilerplate-email
```

<li>Get into the folder: <code>cd boilerplate-email</code>.</li>
<li>Using the content on <strong>Deployment</strong> page. Add the WeDeploy remote url:</li>

```xml
git remote add wedeploy http://git.wedeploy.com/<projectID>.git
```

<li>Push your data to wedeploy git server: <code>git push wedeploy master</code>.</li>
<li>Once you see it in the Dashboard, your container will be ready to be used.</li>

```xml
http://emaildemo.wedeploy.io
```

</ol>

</article>

## What's next?

* That's it! Now we're ready to start [sending emails to our users](/docs/email/sending-email.html).
