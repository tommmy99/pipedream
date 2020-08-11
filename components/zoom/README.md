# Zoom API Integrations 
### Integrate Zoom and thousands of applications with Pipedream.  Free for developers.

---

Pipedream is a serverless integration and compute platform.  We provide a free, hosted platform that makes it easy to connect apps and develop, execute and maintain event-driven workflows.

**Key Features**:
* [Zoom API Event Sources](#github-api-event-sources) - Open source [components](https://github.com/PipedreamHQ/pipedream/tree/master/components) that emit events from Github
* [Workflows](#workflows) - A sequence of linear steps - just Node.js code - triggered by a Github event
* Serverless - No server or cloud resources to manage
* [Free](#pricing) - No fees for individual developers (see [limits](https://docs.pipedream.com/limits/))

<a href="http://tod.ly/3fMdryW"><img src="https://i.ibb.co/m0bBsSL/deploy-clean.png" height="35"></a>

## Zoom API Event Sources

 - [Custom Events](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/custom-event.js))
 - [Meeting Created](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/meeting-created.js))
 - [Meeting Deleted](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/meeting-deleted.js)) 
 - [Meeting Ended](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/meeting-ended.js)) 
 - [Meeting Started](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/meeting-started.js))
 - [Meeting Updated](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/meeting-updated.js)) 
 - [Meeting Recording Completed](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/recording-completed.js)) 
 - [Webinar Created](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/webinar-created.js))
 - [Webinar Deleted](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/webinar-deleted.js)) 
 - [Webinar Ended](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/webinar-ended.js)) 
 - [Webinar Started](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/webinar-started.js))
 - [Webinar Updated](http://tod.ly/31IFFFb - Build your own event source using one or multiple events ([code](https://github.com/PipedreamHQ/pipedream/blob/master/components/zoom/webinar-updated.js))   
 
Event sources can also be deployed via the [Pipedream CLI](https://docs.pipedream.com/cli/reference/):

```bash
curl https://cli.pipedream.com/install | sh
```

Once installed, you can deploy an event source by running:

```bash
pd deploy   # prompts you to select a component and pass required options
```

## Workflows

Workflows are a sequence of linear [steps](https://docs.pipedream.com/workflows/steps) - just Node.js code - triggered by an event (via event source, HTTP endpoint, or timer). Workflows make it easy to transform data and integrate with 300+ APIs from various apps and services.

* Trigger your workflow on any [Github event](https://pipedream.com/sources/new?app=github), a different event (e.g. [HTTP requests](https://docs.pipedream.com/workflows/steps/triggers/#http) or a [schedule](https://docs.pipedream.com/workflows/steps/triggers/#cron-scheduler)).
* Add steps to run [Node.js code](https://docs.pipedream.com/workflows/steps/code/) (using virtually any npm package) and [pre-built actions](https://docs.pipedream.com/workflows/steps/actions/).
* Steps are executed in the order they appear in your workflow.
* Data is shared between steps via [step exports](https://docs.pipedream.com/workflows/steps/#step-exports).

Workflow code is [public by default](https://docs.pipedream.com/public-workflows/) so the community can discover and [copy them](https://docs.pipedream.com/workflows/copy/). Your workflow execution and event data is private. 

You can copy [this example workflow](https://pipedream.com/@tod/use-http-requests-to-trigger-a-workflow-p_6lCy5y/readme) to get started, or review some [community-developed workflows](https://pipedream.com/explore) to see what others are building.

## Other Popular API Integrations

* [Airtable](https://github.com/PipedreamHQ/pipedream/tree/master/components/airtable) ([deploy](https://pipedream.com/sources/new?app=airtable))
* [AWS](https://github.com/PipedreamHQ/pipedream/tree/master/components/aws) ([deploy](https://pipedream.com/sources/new?app=aws))
* [Dropbox](https://github.com/PipedreamHQ/pipedream/tree/master/components/dropbox) ([deploy](https://pipedream.com/sources/new?app=dropbox))
* [Github](https://github.com/PipedreamHQ/pipedream/tree/master/components/github) ([deploy](https://pipedream.com/sources/new?app=github))
* [Google Calendar](https://github.com/PipedreamHQ/pipedream/tree/master/components/google-calendar) ([deploy](https://pipedream.com/sources/new?app=google-calendar))
* [Google Drive](https://github.com/PipedreamHQ/pipedream/tree/master/components/google-drive) ([deploy](https://pipedream.com/sources/new?app=google-drive))
* [RSS](https://github.com/PipedreamHQ/pipedream/tree/master/components/rss) ([deploy](https://pipedream.com/sources/new?app=rss))
* [Twitter](https://github.com/PipedreamHQ/pipedream/tree/master/components/twitter) ([deploy](https://pipedream.com/sources/new?app=twitter))

## Pricing

Pipedream is currently free, subject to the [limits noted below](https://docs.pipedream.com/limits/). Paid tiers for higher volumes are coming soon.

If you exceed any of these limits, please [reach out](https://docs.pipedream.com/support/).

## Getting Support

You can get help [on our public Slack](https://pipedream.com/community) or [reach out to our team directly](https://docs.pipedream.com/support/) with any questions or feedback. We'd love to hear from you!

## Found a Bug? Have a Feature to suggest?

Before adding an issue, please search the [existing issues](https://github.com/PipedreamHQ/pipedream/issues) or [reach out to our team](https://docs.pipedream.com/support/) to see if a similar request already exists.

If an issue exists, please [add a reaction](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-conversations-on-github) or comment on your specific use case.




## Zoom

This directory contains [event sources](https://docs.pipedream.com/event-sources/) that operate on data from the [Zoom API](https://marketplace.zoom.us/docs/api-reference/introduction).

Event sources let you turn any API into an event stream. For example, the [`recording-completed.js`](recording-completed.js) event source polls the Zoom API for new meeting or webinar recordings tied to your user, and [emits](https://github.com/PipedreamHQ/pipedream/blob/master/COMPONENT-API.md#thisemit) a new event for every new recording it finds. You can access these events in real-time using a [private SSE stream](https://docs.pipedream.com/api/sse/) tied to your source, or in batch using the [REST API](https://docs.pipedream.com/api/rest/). Or you can trigger [Pipedream workflows](#pipedream-workflows) on every new event.

[Read more in the Zoom + Pipedream docs](http://docs.pipedream.com/apps/zoom/).

### Pipedream workflows

You can trigger a [Pipedream workflow](https://docs.pipedream.com/workflows/) — hosted Node.js code — on every new event from any Zoom source. You can find a few example workflows below.

To use a workflow, just **Copy** it and follow the instructions in the workflow's `README`. You can modify or extend these workflows in any way you'd like.

- [Save Zoom recordings to Amazon S3, then delete Zoom recording](https://pipedream.com/@dylburger/save-zoom-recordings-to-amazon-s3-p_PACKJG/readme)

For a deeper introduction to Pipedream and event sources, see the [root `README` in this repo](/README.md), the [component API](/COMPONENT-API.md), or the [docs](http://docs.pipedream.com/apps/zoom/).