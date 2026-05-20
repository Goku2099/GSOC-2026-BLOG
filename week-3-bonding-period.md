GSoC Bonding Period — Week 3

This week was again focused on understanding the codebase, running everything locally, and handling the bugs I encountered during testing.

One of the biggest learnings for me this week was understanding how the SDK architecture actually works internally, how different workflows are connected, and how things move across the system behind the scenes.

While testing locally, I also discovered a workflow-related bug. Initially I thought the issue was limited to one repository, but while debugging deeper I realized the problem was connected with another repo — spark-operator. So currently I’m still exploring the flow properly and working towards a clean fix instead of patching it blindly.

Honestly, this entire phase of exploration and debugging feels exciting.

Sometimes you spend hours tracing logs, workflows, pods, port-forwarding, cluster states, and internal execution paths just to understand why one thing failed. But that process teaches a lot more than simply reading documentation.

I genuinely feel like I’m growing 2x or even 5x faster just by:

* cross-questioning things
* discussing approaches with mentors
* giving demos during meetings
* and continuously debugging real workflows locally

This week I also learned a few new debugging techniques that are helping me a lot while diagnosing issues.

For new contributors:

If your only reason for entering open source is “getting into GSoC”, then your goal is probably too narrow.

GSoC is not the final destination. The actual purpose is contributing to open source, learning how large systems work, collaborating with communities, and growing as an engineer through real problem-solving.

If you genuinely want to contribute or start with open source and feel stuck somewhere, feel free to ask me questions anytime. I’ll try my best to help.

