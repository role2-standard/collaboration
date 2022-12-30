[中文](./readme.zh.md)

# Role2 Collaboration Standards

[Role2 Developer Collaboration Standards](./developer/index.md)

```text
scope: All collaboration scenarios
```

## Principle

**Goal is the king, everything serves the king.**

### Goal-oriented

What is a goal? Goal is defined as **maintaining something to an ideal state**, which requires effort in most cases.

#### Principle

**Small goals follow big goals**

A big goal is the current goal's parent goal. For instance, eat well and sleep well are sub-goals of survive; shop grocery and boil the water could be sub-goals of cooking. If a goal contradicts to its sub-goals, then those sub-goals are considered as invalid and should be discarded.

#### Make it written

The implicit sub-goal of every goal is to make it known, which is equivalent to creating a task in a project management software, for example. Write down every task properly is beneficial because:

- Teammates could have a clearer expectation ("Since he'll finish the poster design tomorrow, I can get the page structure done first so that it can be ready by then")
- Outcome can be quantified and assessed more easily
- Tasks are easier to refer to

#### Format

A valid goal includes three compulsory fields: **Name**, **Person in charge**, **Estimated completion time**.

##### Title

Every goal must be an imperative sentence, meaning that the goal shall **include verb(s)**:

- **Submit** website filings (✔)
- **Implement** entry of admin page (✔)
- **Understand and record** customers' concerns (✔)
- Website filings (×)
- Entry of admin page (×)
- Customers' concerns (×)

##### Person in charge

The person (people) who will lead the progress of this goal. Aside from this individual, all relevant people could be assigned as well so that when the state of the goal changes (e.g. estimated time, state of completion), the rest will be informed.

##### Estimated completion time

It could set people's expectation regarding the duration of a task, so that further plans can be made. For something that isn't possible to estimate the duration, you need to specify the reason.

#### Who can specify the goal (task)

Everyone. As long as the goal can be proved to be necessary.

Necessary goals: sub-goals that are essential to larger goals.

#### When should a goal (task) be created

Anything that can't be done in 10 minutes needs to be specified as a goal. This includes things like planning and contemplating, which are usually "invisible". 

## Requirements

- Divide the tasks accurately
- Broadcast the status timely

### Divide the tasks

Requirements:

- **Feasable for a single person**: each smaller task can be completed by a single person.

#### Feasable for a single person

A task being feasable for a single person means the individual who was assigned to this goal can actually achieve it, either by completing it on his own (e.g. a developer role) or dividing it appropriately (e.g. a manager role).

### Broadcast in time

Broadcasting your progress is very important. Everyone sticking to their own tasks seems to be fine, but that could also make everyone become a blackbox. Incorrect broadcast or no broadcast at all could significantly increase the effort required for collaboration as well as the uncertainty of the project. On the other hand, accurate and timely broadcast enables everyone to take actions under the same context, which contributes to the overall efficiency.

Let your teammates be aware of your status. For example:

- What I'm doing (I've arrived at the clients' place and am waiting for the them to finish the previous meeting.)
- How is everything going (Clients feel the price is a bit too high)
- Whether assistance is required. If so, what's the exact content ("@whh, have we developed the module for data analysis?")
- Your expectations (The client seems to be interested, I'll ask him again tomorrow.)
- Which condition you are waiting for it to be fulfilled ("Give them a couple of days to consider.")

#### Who to broadcast

Superior leaders as well as other peers of the same level.

#### What to broadcast

Everything that could potentially affect other team members should be broadcasted, and no question is necessary. If someone asks a question regarding your work, then the broadcast was not done correctly.

Typical broadcast examples:

- Is everything going well?
  - Yes, everything is proceeding as planned.
  - If not, then what problems did you encounter? What type of assistance is needed? Which conditions are you waiting for it to be fulfilled?

Examples:

- (A follow-up task) Just discussed with clients and they have some concerns related to data security.
- (An implementation task) A 3rd party library is needed, which I haven't learned about. I need to spend some time on reading its documentation and it could take a while.
- (Attending a meeting) The time for that meeting is still to be determined due to epidemic. @whh should I just go back or wait a bit longer?
-

#### Where to broadcast

You should be aware of the broadcast whenever and wherever you are. Comments received after creating a task or communication with relevant people could all involve broadcasting.

The best place to broadcast is the sub tasks of a main task or its comment section, where context and timestamps that could be used to show the progress are also available.
