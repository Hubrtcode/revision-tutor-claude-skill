# revision-tutor-claude-skill
 # 📓 revision-tutor

A Claude skill that turns your AI into a proper revision tutor, not the kind that just dumps notes at you, but the kind that actually quizzes you, tells you when you're wrong, and makes you think.

Built for GCSE and A-Level students. Works with any subject.

---

## what it does

- Asks you questions **one at a time**, topic by topic
- Pulls questions straight from your past papers and mark schemes if you upload them
- Scales the number of questions per topic based on how often it comes up in exams (1–5 questions)
- Gives you honest feedback, it won't just agree with you if you're wrong
- Generates clean **notebook notes** after each topic that you can actually copy down
- Optionally saves those notes straight to a **Google Doc** so you don't lose them

---

## how to install

1. Download `revision-tutor.skill`
2. Open [claude.ai](https://claude.ai)
3. Go to **Settings → Skills → Upload a skill**
4. Upload the file
5. Done, Claude will use it automatically whenever you ask to revise something

---

## how to use it

Just start a conversation naturally:

> *"quiz me on biology unit 2"*
> *"help me revise the design process"*
> *"test me on everything"*

Claude will pick it up and run the setup flow before starting:

1. **Past papers** — upload them, point to project files, or skip
2. **Extra resources** — textbooks, revision guides, PDFs
3. **Google Docs** — save notes automatically after each topic (optional)

Then it generates a syllabus, you pick a topic (or just say "let's go"), and it starts quizzing you.

---

## what a session looks like

```
Claude:  What are the 4 types of motion? Give a real-life example of each.

You:     linear, rotary, oscillating, reciprocating

Claude:  Names are all correct ✅ — but I asked for examples too.
         Give me one real-life example for each now.

You:     linear = lift, rotary = car wheel, oscillating = windshield wipers,
         reciprocating = idk

Claude:  Reciprocating = back and forth in a straight line.
         Think a piston in a car engine, or a sewing machine needle.
         Easy way to remember: oscillating swings in an arc, reciprocating goes straight.
```

After all questions on a topic are done, it generates notes like this:

```
📓 Mechanisms — Notebook Notes

Types of Motion:
| Type          | Description                  | Example            |
|---------------|------------------------------|--------------------|
| Linear        | Straight line, one direction | Lift, drawer       |
| Rotary        | Circular/spinning            | Car wheel          |
| Oscillating   | Back and forth in an arc     | Windshield wipers  |
| Reciprocating | Back and forth, straight     | Piston, sewing needle |

Formulas:
- MA = Load ÷ Effort
- Gear ratio = driven teeth ÷ driver teeth
...
```

---

## supported exam boards

When you say you don't know where to get past papers, it'll ask your board and send you straight there:

- **CCEA** → ccea.org.uk/qualifications
- **AQA** → aqa.org.uk/past-papers
- **Edexcel** → qualifications.pearson.com/past-papers
- **OCR** → ocr.org.uk/administration/support-and-tools/past-papers
- **WJEC** → wjec.co.uk/resources

---

## ⚠️ heads up

This skill was built with AI and while it does its best to give accurate, exam-focused content, **it can and does make mistakes.** Answers, definitions, and notes should be double checked against your textbook, mark schemes, or your actual teacher before you commit them to memory.

Think of it as a study partner, not a source of truth. It's great for drilling knowledge and flagging gaps, but your teacher and official mark schemes have the final word.

---

## requirements

- A [Claude.ai](https://claude.ai) account (free tier works)
- The `.skill` file from this repo
- Past papers are optional but make it way better

---

## contributing

If you spot something wrong, have a subject you want better coverage for, or want to improve the skill, PRs are welcome. Just keep the tone casual and the focus on what actually helps students pass exams.

---

*made with Claude · always double check with your teacher*
