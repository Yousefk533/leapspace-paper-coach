# Improve a paper with LeapSpace

This package gives an AI the instructions for a feedback-and-revision workflow. It is a skill, not a separate app. It can be used as an instruction file by Codex, Claude, or another assistant; automatic operation requires that assistant to have browser access to LeapSpace and tools to edit your paper.

## The easiest way to use it

1. Open an AI assistant that can control your browser and edit documents.
2. Sign in to LeapSpace in a browser that the assistant can access.
3. Attach `SKILL.md` and your paper to the AI chat. If the assistant supports importing skills, you can install the skill folder instead. If it cannot read an attached instruction file, paste the contents of `SKILL.md` into the chat.
4. Send the message below, replacing the target.

> Follow the attached LeapSpace Paper Coach skill. Improve the attached paper for Materials Advances. I authorize sharing this paper with LeapSpace to obtain feedback. Preserve my original and return a separate revised Word document. Run up to three feedback-and-revision rounds automatically, verify what LeapSpace can read, and stop if further progress needs my data or a decision. Give me the revised paper and a brief change record. Do not submit it to the journal.

For a class paper, replace the journal with “my class assignment” and attach the assignment instructions if you have them. If you have no specific target, say “general academic clarity and accuracy.”

For each new paper, the AI first asks what it is intended for and which requirements to follow. This includes journals, master's or doctoral theses, class assignments, research proposals, and other purposes. Answer with the target and any guidelines you have, or say “general academic improvement.” If you already provided details, it asks only about what is missing or whether there are additional requirements. It waits for your answer before starting the feedback-and-revision loop.

After this opening exchange and setup, the AI should handle ordinary feedback rounds itself. It may still need you for sign-in, a required permission, missing research data, or an author decision. A chat-only AI without browser tools can explain the process, but cannot operate LeapSpace automatically.

## What you should receive

A separate revised paper, a short account of changes, and any remaining questions. The AI should state how many rounds it completed and whether LeapSpace reviewed the whole paper or only some sections.

The skill includes a check for a problem found during testing: LeapSpace's assistant sometimes saw only an excerpt even though the full essay was visible in its editor. It must detect incomplete access and test section-by-section review rather than pretend the entire paper was reviewed.

This package has no passwords, API keys, paid software, or installer. The instructions do not create a direct API connection or make an assistant run indefinitely. The AI host's permissions and your LeapSpace access still apply.
