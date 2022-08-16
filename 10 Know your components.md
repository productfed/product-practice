In medium/high complexity platform architectures, some components need dedicated attention and maintenance.

This can generally be due to their nature, their size, or both.

For development teams, being responsible for a component means supporting it, and its users.
In the "best case" scenario, the team who built a component is the same team who supports it.
If that is true, roles and responsibilities are clear, and the team is less likely to encounter blockers.

Often times, however, the support for a component passes over to teams who had little to no involvement in its creation/development.
In this scenario, teams are more exposed to complexities and risks, which make it harder to support users.
Roles and responsibilities are less clear and teams suffer from a higher degree of knowledge gaps.

In practice, supporting a component that you did not build, can be much, much harder.

##

To make this "inherited" support less hard, there are three main aspects that we can address.

#### 1. "feeling" about components: this is abut making the most of the current level of experience of your team members.

The longer people have worked on teams, the higher is the likelihood that they have encountered issues with a supported component.

Trust the experience of those developers for your estimates and remediation/resolution plans.

They will have a good understanding of what was the problem they had to solve, and how much effort it required to fix it.
They may have fixed recurring issues.
They may have found patterns between different issues.

Furthermore, they may have ideas on how to improve those components, to make it so they are more reliable in the future.


#### 2. Understand how it's really running: this is about learning how it was built and how it works.

Especially useful if your team has not build the component.
Especially useful if the component is complex.

Especially useful because, if both of the above apply, your chain of support is at high risk.

Do everything you can, to learn as much as possible about your component.
Prioritise stories related to it.
Treat it as a core part of your mission.

Make it so your developers pair as much as possible.

Add relevant tests, where you see fit.
Add notifications to learn about behaviours and errors.
Build a monitoring system if it can help you automate, while reducing the support burden.


#### 3. Build FAQs or playbooks incrementally: this is about how to build and foster your knowledge, while facilitating your work.

It is good practice to build some "how to" documentation, for the maintenance of a specific component.

Put it together incrementally, step by step.
Make it so all the developers in your team contribute to it.
Make it part of the acceptance criteria for every user story written to fix an issue with the component.

If you want to use it to answer questions to recurring issues, use the "frequently asked questions" format.

If you want to use it to increase consistency and speed of resolution, build it as a [runbook](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.runbook.en.html).

If you want to use it to increase team awareness, build it as a [playbook](https://wa.aws.amazon.com/wellarchitected/2020-07-02T19-33-23/wat.concept.playbook.en.html).

If the component is high risk/value, you can simulate incidents in a similar format to a [disaster role playing](https://sre.google/sre-book/accelerating-sre-on-call/#xref_training_disaster-rpg) exercise. You can capture the steps of your rehearsal into a [template](https://docs.google.com/document/d/1UWcKUSKnyv8DVX1FUSYy0UOt72u6WLDqLqHg9lqeyro/edit), from which information can be later fed into your main documentation.

Feel free to [adapt](https://technology.blog.gov.uk/2021/03/04/wheel-of-misfortune-incident-rehearsal-for-gov-uk-paas/) the exercise to your needs. Do what matters to you and your team.
