# How to apply for Alumni Society

Applying to join the Alumni Society is easy and straight-forward. Just fill out the info directory form, wait for your entry to be reviewed and you are good to go.

## Requirements

* A Hack Clubber with a non-deactivated Hack Club Slack account and no active
CoC strikes in the past 90 days
  * In the event of a permanent ban due to CoC violations or fraud/abuse, 
  * You don't need to be verified as an student before applying, although it is best to do so while you are still eligible.
  * If your account is deactivated for reasons other those stated earlier, you may still apply but you need to [use this form instead].
* An account on any of these code forges with 2FA enabled:
  * [Nest's Forgejo instance](https://git.hackclub.app)
  * [GitHub](https://github.com)
  * [GitLab SaaS](https://gitlab.com)

## How to apply

### In the Slack

1. Join the public `#alumni` channel in Hack Club Slack.
2. Run the `Join the alumni society's private channel` workflow in the featured workflow.

![that featured workflow in question](https://hc-cdn.hel1.your-objectstorage.com/s/v3/381cea766733f04d1b41e0b2bf5c49f2208272d9_screenshot_20250914-113244.jpg)

3. Follow the instructions sent via DMs from the workflow. After that, you will be admitted via the Alumni Society Ops Slack bot once approved by a fellow alum.
4. In case of rejection, check your DMs for more information. You may try again after 14 days by pressing `Re-apply` button in the DM.

### Via Fillout

> ![NOTE]
> This Fillout form is managed through Recap Time Squad's Fillout team, but managed by @ajhalili2006 directly.

If you prefer to fill out forms outside the Slack or can't access Hack Club Slack right now, [here's the Fillout link](https://recaptimedev.fillout.com/alumni-society-apply). Check your email in 1-2 days for updates.

## Why I was rejected?

If you committed fraud (e.g. Hackatime banned) or abuse (e.g. breaking Nest's Acceptable Use Policy) or broke the hack Club Code of Conduct, you will not able to join the Alumni Society out of caution. You must appeal any sanctions with [the Code of Conduct Working Team] or wait until they expire (if they are
not permanent or serious enough).

Another might be you are still active within the Hack Club community in one way or another, be it in eligibility status for grants or even being a HQ/HCB staff. If this is you, don't worry, you will be admitted soon. Please do not re-submit the form as it will cause duplicates on our side.

## Instructions for alumni members

### For Slack submissions

1. Once they submit their details to the Alumni Society Directory in Slack, look at their entry in the list. If you have questions about their submission, just DM there or write a email.
2. To approve and admit to the channel + user group, run `/alumni-society admit @mention-them-here`, replacing `@mention-them-here` by mentioning their Slack profile.
    - If happens to be submitted via the alternative form, run `/alumni-society admit fillout_`, replacing `ID` with the submission ID from Fillout API.
3. To deny, run `/alumni-society deny <mention or fillout submission ID>` and follow the prompts in the modal.

### For Fillout submissions

See above for the Slack bot commands, but the rest of this section is for spaces outside the Slack.

TODO: Document access provisioning to other resources like GitHub/Nest Forgejo/GitLab SaaS.

[the Code of Conduct Working Team]: ../CODE_OF_CONDUCT.md#working-group