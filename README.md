# Orb Template


This is [slack-orb](https://github.com/CircleCI-Public/slack-orb) (v4.12.1) but w/ the ability to bypass certificate verification by setting the `TURN_OFF_CERT_VERIFICATION` environment variable.

--
## Resources

[CircleCI Orb Registry Page](https://circleci.com/orbs/registry/orb/slm-zhong/slack-orb-optional-cert) - The official registry page of this orb for all versions, executors, commands, and jobs described.

[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using, creating, and publishing CircleCI Orbs.

### How to Contribute

We welcome [issues](https://github.com/ZhongRabbit/slack-orb-optional-cert/issues) to and [pull requests](https://github.com/ZhongRabbit/slack-orb-optional-cert/pulls) against this repository!

### How to Publish An Update
1. Merge pull requests with desired changes to the main branch.
    - For the best experience, squash-and-merge and use [Conventional Commit Messages](https://conventionalcommits.org/).
2. Find the current version of the orb.
    - You can run `circleci orb info slm-zhong/slack-orb-optional-cert | grep "Latest"` to see the current version.
3. Create a [new Release](https://github.com/ZhongRabbit/slack-orb-optional-cert/releases/new) on GitHub.
    - Click "Choose a tag" and _create_ a new [semantically versioned](http://semver.org/) tag. (ex: v1.0.0)
      - We will have an opportunity to change this before we publish if needed after the next step.
4.  Click _"+ Auto-generate release notes"_.
    - This will create a summary of all of the merged pull requests since the previous release.
    - If you have used _[Conventional Commit Messages](https://conventionalcommits.org/)_ it will be easy to determine what types of changes were made, allowing you to ensure the correct version tag is being published.
5. Now ensure the version tag selected is semantically accurate based on the changes included.
6. Click _"Publish Release"_.
    - This will push a new tag and trigger your publishing pipeline on CircleCI.