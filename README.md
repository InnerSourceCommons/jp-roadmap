# InnerSource Community Toolkit

When you are starting an InnerSource Community, you will need a toolkit to get your community off the ground quickly.
This is true no matter whether your community is a company-internal activity, a regional community, or a specific business-to-business sharing group.

Luckily this toolkit by the [InnerSource Commons](https://innersourcecommons.org) is just what you need to get your InnerSource community started. :)

## Existing communities

* [Japan](./japan) - This is the first regional community that formed. Therefore much of the material in here was extracted from their work.
  * communcation happens in Slack via `#jp-general` and `#jp-contents`
  * with the tag "**Japan :jp:**" you can filter for their [issues](https://github.com/InnerSourceCommons/community-toolkit/labels/Japan%20%3Ajp%3A) and [discussions](https://github.com/InnerSourceCommons/community-toolkit/discussions?discussions_q=label%3A%22Japan+%3Ajp%3A%22)
  * their [Public Community Roadmap](https://github.com/orgs/InnerSourceCommons/projects/1) shows their plans for the coming quarters
* [Brazil](./brazil) - You find them in `#innersource-brazil`. Their directory in here was just created.
* [Thailand](./thailand) - Their directory in here was just created.

## How to create your community directory

Building on the structure of the [international](./international) directory is a good starting point.
You can customize the directory structure, but try to keep the base as close as possible so that other communities can easily refer to it.

The following commands may be helpful:

```sh
rsync -avz --include "*/" --exclude "*" international/ <YOUR_COMMUNITY_NAME>
find <YOUR_COMMUNITY_NAME>/ | xargs -I BASEPATH touch BASEPATH/.keep
```

## Questions?

This toolkit is really new!

Please contact us in `#local-community` in [Slack](https://innersourcecommons-inviter.herokuapp.com) with any questions.
