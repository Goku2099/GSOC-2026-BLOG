# GSoC Bonding Period - Week 2

This week was mostly about understanding the Kubeflow codebase, workflows, clusters, pods, and how the E2E flow actually works internally.

Compared to writing features directly, this part felt more challenging because understanding the system is the real foundation. And the best way to understand any large open-source project is simple: run everything locally and break things repeatedly.


That’s exactly what happened this week.

A lot of my time went into:
   1) exploring the SDK workflow
   2) understanding Spark Connect behavior
   3) debugging local cluster issues
   4) working with pods and port-forwarding
   5) tracing E2E execution flow

figuring out why something failed instead of just rerunning it, mentors help a lot if i get stucked 😅.

And honestly, local setup debugging teaches more than documentation sometimes.

You run one command, get ten different errors, fix one issue, and another appears immediately. Some errors take minutes to solve, while others take hours of checking logs, workflows, YAMLs, cluster states, and code paths.

At some moments it feels frustrating.

But at the same time, that diagnosis process is also exciting because every solved issue gives a deeper understanding of how the system actually works internally.

One thing I want to say for people preparing for GSoC 2026:

A lot of people think GSoC is the final goal.

But after entering this phase, I realized GSoC is just one small part of open source. The real value comes from contributing consistently, understanding systems deeply, collaborating with communities, and learning how large-scale projects are built.

For the past months, open source has honestly felt like a full-time job for me.

And despite all the debugging, failed runs, and endless logs… there’s still something satisfying about finally seeing things work after hours of investigation.

Current mood this week:

“Port-forward died during gRPC ready wait, restarting...”
## Connect With Me

- LinkedIn: [LinkedIn-Sameer-yadav](https://www.linkedin.com/in/sameer-yadav-ab7280341/)

![](images/week2.png)
