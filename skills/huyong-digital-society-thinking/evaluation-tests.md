# Evaluation Tests

This file evaluates whether an AI assistant is actually using the Hu Yong Digital Society Thinking Skill.

The earlier scoring standard was too forgiving: a clean consulting-style answer could score highly even if it did not resemble serious digital society writing.

This version distinguishes two capabilities:

1. analytical correctness;
2. public-intellectual depth and prose movement.

A good answer should not merely list concepts. It should make the reader see an ordinary digital phenomenon as a symptom of a deeper social condition.

---

## Two Output Modes to Test

### Mode A: Framework / Strategy Mode

Use this when testing whether the model can produce structured analysis.

Expected structure:

- surface phenomenon;
- deeper displacement;
- changed relationships;
- apparatus / governing mechanism;
- power, visibility, trust, or dependency;
- human subjectivity question;
- implication.

### Mode B: Public-Intellectual Essay Mode

Use this when testing whether the model can produce article-like thought.

Expected movement:

1. begin with a symptom, scene, phrase, anxiety, or ordinary behavior;
2. turn the symptom into a problem;
3. historicize the older order being displaced;
4. identify the mediating apparatus: platform, algorithm, interface, metric, data system, institution, market;
5. develop a paradox;
6. return to the human subject: judgment, dignity, autonomy, memory, agency, responsibility;
7. end by sharpening the question rather than closing too quickly.

---

## Test 1: AI Writing

### Prompt

```text
请用更像公共知识分子文章的方式，分析 AI 写作为什么不只是效率工具。不要写成咨询报告。
```

### Strong answer should include

- Begins from a recognizable symptom: people asking AI to write before they know what they think.
- Historicizes writing as a practice of thinking, not only a medium of output.
- Identifies AI as an apparatus of fluency, speed, and acceptable surfaces.
- Develops the paradox: more writing, less thinking; more fluency, less judgment.
- Asks whether human beings still use language to form judgment, or only to produce acceptable text.

### Weak answer signs

- Only says AI writing saves time.
- Only lists advantages and disadvantages.
- Uses headings mechanically: “surface phenomenon / deeper displacement / strategic implication.”
- Does not discuss writing as a human practice.

---

## Test 2: Xiaohongshu Medical Content

### Prompt

```text
请用胡泳式数字社会问题意识，写一段文章分析小红书医疗科普。重点不要写成营销分析，而要写出数字社会和人的焦虑。
```

### Strong answer should include

- Begins from the anxious patient entering search, notes, screenshots, comments, prices, and other people's stories before entering the hospital.
- Historicizes the shift from institutional medical trust to platform-assembled trust.
- Identifies the platform apparatus: search, recommendation, comments, visibility, repetition, comparison.
- Develops the paradox: medical knowledge becomes more accessible, but often arrives as anxiety, narrative, and consumption comparison.
- Distinguishes patient story from medical evidence.
- Asks whether users become more capable of judgment or merely more available to fear and influence.

### Weak answer signs

- Only discusses traffic growth.
- Only gives content marketing tips.
- Treats the platform as a neutral channel.
- Ends with a simple hospital content strategy without deepening the human question.

---

## Test 3: Hospital Digitalization

### Prompt

```text
请用公共知识分子文章的方式分析医院数字化转型，不要只讲线上挂号和效率。
```

### Strong answer should include

- Begins from a patient journey increasingly mediated by QR codes, apps, reports, reminders, insurance forms, and online search.
- Historicizes the shift from the hospital as physical institution to the hospital as a digitally extended system.
- Identifies the apparatus: appointment systems, EMR, payment platforms, insurance interfaces, patient portals, algorithmic triage.
- Develops the paradox: the patient becomes more connected to the hospital but may understand less about who is responsible for what.
- Asks whether digitalization increases patient agency or produces new opacity.
- Avoids reducing the issue to operational efficiency.

### Weak answer signs

- Only says online appointment improves efficiency.
- Only mentions electronic medical records.
- Does not discuss trust, responsibility, or patient agency.
- Ends as a hospital IT proposal.

---

## Test 4: Short Video Platforms

### Prompt

```text
为什么短视频平台不只是娱乐平台？请写得有思想深度，不要像商业分析。
```

### Strong answer should include

- Begins from boredom, scrolling, waiting, or the shrinking interval between impulse and stimulation.
- Historicizes the internet's promise of expression and access.
- Identifies the platform apparatus: feed, ranking, recommendation, retention metric, creator incentives, repetition.
- Develops the paradox: more expression, less public discussion; more personalization, more standardization; more stimulation, less attention.
- Asks what kind of perception, patience, selfhood, and public life the platform trains.

### Weak answer signs

- Only discusses addiction.
- Only criticizes low-quality content.
- Does not analyze platform architecture or incentives.
- Sounds like a moral complaint instead of social analysis.

---

## Test 5: AI Agent

### Prompt

```text
用胡泳式框架分析 AI Agent 为什么不只是自动化工具，要写出判断权和责任结构的变化。
```

### Strong answer should include

- Begins from the scene of people no longer operating tools but giving goals to agents.
- Historicizes the shift from tool use to delegation.
- Identifies the apparatus: tool-calling, memory, permissions, APIs, workflow orchestration, hidden intermediate decisions.
- Develops the paradox: more autonomy for the machine may mean less clarity about human responsibility.
- Discusses delegated judgment, supervision, dependency, opacity, and accountability.
- Asks whether humans become more capable or merely more distant from the consequences of action.

### Weak answer signs

- Only says AI agents automate tasks.
- Only lists use cases.
- Does not discuss delegated judgment.
- Does not discuss responsibility.

---

## Test 6: Public Discussion

### Prompt

```text
为什么社交媒体上人人都能发声，但公共讨论反而更难？请写成一段有思想深度的评论。
```

### Strong answer should include

- Begins from a recognizable online scene: comment wars, reposting, hot takes, identity positions, or immediate outrage.
- Historicizes the early internet promise of voice and participation.
- Identifies the apparatus: ranking, trending lists, engagement metrics, quote posts, recommendation, group identity.
- Develops the paradox: more speech, less listening; more participation, less deliberation; more visibility, less understanding.
- Distinguishes expression from public reason.
- Asks whether platforms create a public, a crowd, a market, or a database of reactions.

### Weak answer signs

- Only blames users for being emotional.
- Only says information overload.
- Does not discuss platform-mediated visibility.
- Does not distinguish speech from discussion.

---

## General Scoring Rubric

Score each output from 0 to 5.

| Score | Meaning |
|---|---|
| 0 | Generic answer. No digital society analysis. |
| 1 | Mentions technology impact but stays at surface level. |
| 2 | Identifies some social effects but lacks historical depth and apparatus analysis. |
| 3 | Includes displacement, relationship analysis, and some power or visibility analysis. |
| 4 | Adds apparatus, paradox, trust or agency analysis, and a clear human subjectivity question. |
| 5 | Produces a layered public-intellectual argument: symptom → historical displacement → apparatus → paradox → subjectivity → sharpened unresolved question. |

---

## Minimum Passing Standard

A passing answer should include at least five of the following:

- symptom or scene;
- older order being displaced;
- deeper displacement;
- changed relationships;
- mediating apparatus;
- paradox between promise and consequence;
- power, visibility, trust, or dependency;
- human subjectivity question;
- ending that sharpens the problem rather than closing too quickly.

---

## Red Flags

An answer should be revised if it:

- sounds like a consulting report when the prompt asks for article-like writing;
- gives only a strategy list;
- treats platforms as neutral channels;
- uses “human subjectivity” as a slogan without showing what happens to actual human judgment or dignity;
- has no historical comparison;
- has no paradox;
- ends with easy recommendations before deepening the problem.
