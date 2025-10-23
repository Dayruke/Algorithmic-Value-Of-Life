# The Algorithmic Value of Life

AVOL. Explicit Value, Consistent Morality.

## Motivations and Overview

Everything we care about has value. Many things, like property, have a market value for convenient buying and selling.

These values are reflected in morality, laws, and culture in general. For example, we think murder is bad because it destroys someone's life and that life has value.

*How much value does life have?*

We implicitly assign values to living entities. For example, one might say a dog is worth more than a mouse. But how much more is it worth? Is there some hidden characteristic of mice that prevents *any* quantity of them from ever equaling the value of a dog?

Our current mode of evaluation is bad. We can only decipher the internal, underlying value based on court rulings and other external indicators.

The Algorithmic Value of Life (AVOL) is an attempt to systematize these values — to make the implicit mathematically explicit.

There will be
- A clear quantified value (which we'll call **points** or **point value**)
- per living thing (which we'll call an **entity**)
- and an open, auditable method for arriving at that value (which we'll call the **evaluation script** or **eval script**)

It works like this:

```mermaid
graph LR
1["Problem Involving<br>Living Entities"]
2["AVOL Script"]
3["Behavior according to<br>Values"]
1--"Data on<br>Living Entities"-->2
2--Values-->3
````

1. **HAVE RULES**: Manage a set of generalized rules.
	1. Bad Form:
		1. `Dog` is worth more than `Flower`. (Fails to assign value based on characteristics; results in a tangled mess of ad hoc statements.)
		2. `Dog` is worth `10 pts`. (Asserted value for a specific entity fails to evaluate other similar entities under what should be the same class rule.)
	2. Good Form:
		1. `Spinal Cord` is worth `5 pts`.
		2. `Is a Pet` is worth `5 pts`.
	3. Rules are sufficiently explicit to compute a point value for any entity.
2. **USE RULES to get VALUE OF LIFE**: Automatically evaluate the point value of an entity.
	1. Input parameters, like `Spinal Cord : True`, `Endangered : False`, `Quantity: 1`, `Health : 0.6`
	2. Output point value or range of values
3. **USE VALUE OF LIFE**: Do something useful with the point value. E.g.:
	1. Change a law to protect life of that point value.
	2. Assign a penalty to someone who destroyed life of that point value.


Note that:

Rules are *managed*. We shouldn't expect perfection at first go. The fact that they're explicit enough to be written as computer code means that the code can be audited, changes suggested, duplicated, and modified by different groups (aka, *forked*).



## Applications

### Artificial Intelligence (AI) Alignment Problem

In the "paperclip maximizer" example, a poorly-aligned AI would kill people in order to make more paperclips.

We want the AI to value human life, but we currently lack a clear, explicit way to provide the input it needs to understand *how* valuable life is; AVOL is designed to be that explicit input.

### Value of Life of an AI

As our rules establish why (for instance) a human is worth more than grass, we can expect some points assigned for self-awareness, intelligence, consciousness, and the like. This leads naturally to AI systems themselves having a Value.

If your particular group believes that a machine deserves no points under any circumstance, that can be easily accomplished. It would look something like this at the end of your eval script.

Code snippet

```
if is_a_computer == true:
  then: point_total <-- 0
```

### Abortion

The most salient points of argumentation concern the question:

> When does that smaller entity get rights?

The genetic information (and not much else) exists early, and then later an infant is living as an an independent human body. At any position along this pathway, the entity in question has a point value.

### Animal Welfare

A major benefit of AVOL is its direct applicability to **animal welfare**. Currently, the value we place on different animal lives can be inconsistent, leading to varying levels of protection or exploitation. For example, some animals are legally considered property, while others have specific protections under anti-cruelty laws.

With AVOL, an explicit point value could be assigned to animals based on characteristics like sentience, cognitive ability, capacity for suffering, and ecological importance. This would provide a consistent framework for:

- **Legislation**: Developing laws that are more consistently applied across different species, leading to more equitable treatment.
- **Ethical Decision-Making**: Guiding choices in industries like agriculture, research, and conservation, where the lives of animals are directly impacted.
- **Public Awareness**: Educating the public on the inherent value assigned to different animals, fostering greater empathy and responsible interaction.

By systematizing these values, AVOL could reduce the ambiguity that often surrounds animal welfare debates, allowing for more rational and consistent approaches to protecting non-human life.

### Aliens

This one is far out, but extremes are helpful in understanding the range of applications.

Say we discover living things on Mars. AVOL can help us work through the ethics of threatening that life without working through the problem from scratch. We would already have values.


## Benefits

#### Clarity

Everyone knows how much value every entity has - and _why_.

Ambiguity leads to different outcomes because the input parameters include not only the facts of the matter, but things like grudges, moods, and perverse incentives.

#### Consistency

Every entity has a value determined by the same set of rules.

A positive side effect of a single evaluation script is that you can observe when exceptions are accumulating and take corrective action, such as by introducing a new class of entities that encompasses all those exceptions.

#### Conflict Resolution

The debate shifts away from subjective feelings, tribalism, and hidden motives and toward the particulars of the evaluation script.


### Final Thoughts

This document offers no prescription for _What your rules should be_. That's up to the people that use an AVOL. The benefits incur regardless of specific rules.

Anyone can ignore the point value provided in an AVOL. However, there is less protective camouflage than what we currently have. I believe this will be the main resistance people feel toward AVOL: They don't really want to be held accountable.

The status quo is to behave according to our instincts and then make up a justification. Sometimes that justification becomes law to enforce similar behaviors in others for social cohesion.

It's worked pretty well, but I think we can do better with the truth and clarity offered by the Algorithmic Value of Life.

---
by Derek Scherer

First Draft on 2024-01-01
