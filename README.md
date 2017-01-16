# hs2-aem-commons

This project is a repository of individual AEM packages freely distributed by HS2 Solutions, Inc to help AEM developers
work around bugs, implement new features, and otherwise just "Get Sh*t Done!"

## Features

### hotfix-msm-lockable-deep-properties
This is a hotfix to address a
[documented AEM OOTB limitation](https://docs.adobe.com/docs/en/aem/6-2/develop/extending/msm.html)
where MSM does not operate with deep properties in regards
to using the cq-msm-lockable attribute to disable inheritance when configuring MSM locks on page properties
(cq:propertyInheritanceCancelled).

### on-deploy-scripts-framework
This is a framework to allow developers to create and leverage one-time scripts that run on an AEM server
upon deploy of a code bundle. See the project documentation for use cases and reasons why this can be a huge
time saver for your AEM team!

### on-deploy-scripts-framework-example-scripts
This is an example package used to demonstrate how to leverage the `on-deploy-scripts-framework` project
to implement one-time scripts that run on an AEM server upon deploy of a code bundle.