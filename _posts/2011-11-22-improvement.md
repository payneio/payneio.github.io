---
layout: post
title:  "Continuous  Improvement"
date:   2014-11-22 23:24:20
categories: 20
---

Continuous Improvement
In 20 minutes

“You can’t improve what you don’t measure”
    -- not Deming, nor Drucker *

If you are responsible for a process that is producing suboptimal results, Continuous Improvement (CI) might be your cup of tea. CI strives to create a culture around modelling processes and improving them using disciplined experiments. 

CI encompasses many ideas that should be widely (perhaps wildly) beneficial in most business contexts:

Share responsibility for improvement with each person in the org.
Always keep the customer in mind.
Understand the value produced at each stage of your production processes.
Focus on improving the processes more than hitting a quota.
Improve processes by eliminating waste.

This article explores the nature of CI by reviewing its history. In the process, I hope you’ll get a sense of why it’s a big deal.

CI didn’t always look like it does today. It began simply in the 1930s as statistical methods were applied to business practices. It turns out, though, that CI is generic enough it can improve its own process with experimentation. So, the form and reach of CI has evolved over the past eight decades.

  Shewhart     PDSA           Lean                    NUMMI TQM   6σ  ISO9000       LSD    Lean Startup

The Scientific Revolution
Taylorism. One right way. 1890 to 1930. He was a dick.
The Statistical Revolution

The Plan-Do-Study-Act (PDSA) cycle was an early application of statistical methods to business management. It was an adaptation by W. Edward Deming of earlier ideas by the statistician Walter Shewhart. Deming presented the PDSA cycle in Japan after World War II, helping spur a resurgence in Japanese manufacturing and establishing him as the honorary father of CI. The PDSA model’s conceptual breadth enabled it to evolve alongside developments in CI, so it is still used today. Think of PDSA simply as “experimenting to learn”. You look at your current processes and think “Hey, I wonder if this change would make things better…” (Plan), then you try it out on a small scale (Do) and see if it worked like you hypothesized (Study). If it did, then you implement the change (Act). This is essentially the scientific method as a counterpoint to management by intuition.
Incubation in Japan

While the US discarded scientific and mathematical methods of production in the wake of WWII, Japan adopted them as a core part of their post-war recovery. Toyota, in particular, went all-in resulting in the development of Lean Manufacturing (Lean).

Lean expects line-workers to focus on eliminating waste (muda) from their local processes while managers fill a coaching role. By creating a shared culture of Kaizen (Japanese for “improvement”), the many small improvements by line-workers bubble up to organization-wide efficiencies. 

“All we are doing is looking at the timeline from the moment a customer gives us an order to the point when we collect the cash. And we are reducing that timeline by removing the non value-added wastes.” -- Taiichi Ohno, Toyota

Lean is primarily a management system for “the absolute elimination of waste.” Waste being defined as:
Overproduction
Waiting (queues)
Transportation
Non-value-adding processes
Inventory
Motion
Costs of quality: scrap, rework and inspection

To readily identify waste, Lean prescribes a focus on flow. A primary tool for this purpose is the Kanban board consisting of each work item (a product or other unit of value) represented on a small card and moved progressively through columns representing stages of the production process. Waste is readily seen if cards pile up or stagnate anywhere on the board. Placing a limit on the number of cards in any given column (a Work-in-Process, or WIP Limit) has the beneficial effect of encouraging all members of the production team to address the blocking issue or source of waste to prevent the production line from grinding to a halt. 

Waste may also be called-out in-the-moment by any team member or by automated systems. Some sort of signboard or signal (andon) is used to immediately stop production until the waste is attended to.

To get to the root cause of identified waste, Lean suggests asking the question “Why?” five times. While keeping in mind the answer may involve identifying problems and making changes in one of six areas:

The people involved
The methods currently employed (e.g., policies, procedures, rules, regulations and laws)
Machines used
Materials used
Measurements being taken, or
The environment of the process (e.g., location, time, temperature, and culture)

Through CI, Japan produced high-quality products that dominated electronics and auto industries. It took until the 1980s for American businesses to begin implementing their own version of CI.
The American Response

Keen to understand Toyota’s Lean success, General Motors entered into a joint venture in 1984. Together, they re-opened a GM factory in Fremont, CA named NUMMI. NUMMI had been closed a couple years earlier, partially due to the unruliness of their factory workers. Newly supplied with Lean processes and training, the same workers were soon producing automobiles with quality as good as their Japanese rivals.

In telecommunications and consumer electronics, Motorola responded to Japan’s industry dominance with their own Six Sigma (6σ). 6σ focuses on rigorously defining and standardizing processes to achieve repeatability so precise that only 3 or 4 defects occur out of a million. To attain this, Six Sigma prescribes the Define-Measure-Analyze-Improve-Control (DMAIC) process. It is pretty much the same as PDSA but with a heavily statistical focus on controlling process outputs. Six Sigma practitioners earn belts like Karate students, so if you progress to the rank of Black Belt, you pretty much are doing process improvement coaching all day, every day.

In 1987, standards bodies exerted their influence, pulling together ISO-9000 from existing quality specs for military suppliers. In 2000, it underwent a major rewrite to focus on process quality rather than simply end-product quality. It essentially became a CI process in 2000. Orgs want quality from their suppliers. This has driven the practice of favoring, or requiring, suppliers to have ISO-9000 certification. Certifications have doubled over the past decade to over 1 million globally. Chinese suppliers now account for about a quarter of all ISO-9000 certifications. That’s about 10x the number of US certifications, which seem to be dropping. This is perhaps because accepting external certification drives focus from achieving improvement to achieving compliance with the quality process itself; and the burden of documentation for this “benefit” is itself a source of waste.

TQM hit the peak of its management hype-cycle in the 90s and has experienced slower growth since. In fact, many of the companies most identified with CI, including Toyota, Motorola, 3M and GE are now struggling against stiff competition or cutting back on CI. The manufacturing space may have reached a certain CI saturation point. However, CI concepts ubiquitous in manufacturing have recently been infecting other industries such as service, healthcare, education and IT.
The Expansion to Management
Since managers used CI to improve manufacturing processes, it was only a matter of time before they thought “hey, we can do this same stuff to improve business management processes”. Starting in the 1960’s, Toyota …

Not to be outdone, the US Navy developed their own version of Lean in the late 80s, including an all-in approach to CI with the moniker Total Quality Management (TQM). In TQM, the entire organization is “All Hands on Deck”. This means every person in the org is expected to have a clear understanding of the org’s Vision, Mission, objectives and critical processes and adopt continuous quality improvement as a core value. In TQM, the org adopts quality improvement as one of the primary (if not the primary) activities of the organization as a whole. It’s hard core.
The Expansion to Software

The turn of the millenium saw Lean come to software development in the form of, wait for it, Lean Software Development (LSD). The core focus remained the same, with the primary adaptations being (1) the form of waste and (2) what constitutes the start and end of the value stream. In software development, the process can be thought of as beginning when a feature or product request is made and ending with the deployed implementation.

The 8 principles of LSD (currently) are:
Optimise The Whole (purpose-driven, work on entire value stream)
Focus on Customers
Energize Workers (purpose, challenge, responsibility)
Eliminate Waste (small WIP, Useless features)
Learn First (decide at the last possible moment, learn quickly, rapidly respond)
Deliver Fast (optimize for flow, MVP)
Build Quality In (TDD, automated testing, ci, expect no defects)
Keep Getting Better (attack small failures, test and learn on small things)
*The Limitations of Continuous Improvement

Continuous Improvement is an amazing capability for a process-oriented organization. But as with all things, it has it’s limitations. Let’s not get all “You can’t improve what you don’t measure” about it while invoking the management genius of W. Edward Deming (the Father of CI) or Peter Drucker. Not only because neither Deming nor Drucker ever said it, but because they wouldn’t agree with it.

Deming recognized that managers need to manage even when figures are unattainable. In fact, he said “3% of the problems have figures, 97% of the problems do not.” 

Drucker recognized another limitation of CI. Namely, that much of the improvement of an organization comes not as figures, but in the form of relationships within the organization: “Your first role . . . is the personal one. It is the relationship with people, the development of mutual confidence, the identification of people, the creation of a community. This is something only you can do. It cannot be measured or easily defined. But it is not only a key function. It is one only you can perform.”

Furthermore, as any statistician will tell you, creating models is a tricky business. Not only can you have limited data, wrong data, irrelevant data, underfit the data or overfit the data, the most fundamental problem is that relying on statistics gives you no absolute guarantee that your model may, at some point, just stop working. Deming said, “Every theory is correct in its own world, but the problem is that the theory may not make contact with this world.”

And in the case of highly variable systems, where inputs and requirements are always changing, CI may never get even get off the ground.

The greatest limitation, perhaps even danger, I see with CI is that it has the potential to lull an organization into a self-referential sleep. Deming called it out: “It is a mistake to assume that if everybody does his job, it will be all right. The whole system may be in trouble.” A system can be optimized locally and yet be a complete waste globally.
What Should We Make of CI?
Continuous Improvement, at it’s heart is simply about adopting a disciplined scientific approach to modelling a business process and driving out inefficiencies. Its concepts, experimentally developed for nearly a century, provide a rich set of tools to improve your work (mainly on speed and quality, but also team satisfaction). Just don’t go too crazy out of the gate.

You can get started today with any service or production process you use to deliver value to customers. Break that process into steps, and start looking for waste that keeps any step from moving as smoothly as it can. When you find waste, do a small experiment to see if you can eliminate some or all of it. If you can, then document the new process. 

“Manage the cause, not the result.” -- W. Edward Deming.

Once you start focusing on the process rather than the outcome, you’ll be on your way with Continuous Improvement. There are a billion books to go from there. Amazon will help you find the most popular ones. Also, companies tend to geek out about their CI processes; many of them run tours. A great CI tour in the Seattle area can be had at Kaas Tailored.

