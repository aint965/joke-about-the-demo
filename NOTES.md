# Joke notes — two revision rounds

## Round 1 — five candidates, scored against the judge's criteria

Subject: a joke about AI coding agents, funny about something that crashed.
Criteria order: (1) on-subject, (2) surprise punchline, (3) recognisable truth,
(4) economy, (5) freshness. Stock lines deliberately avoided: "it deleted
everything", "works on my machine", "it fixed the bug by deleting the feature".

1. "My AI agent demoed the app live, it crashed, and the agent said, 'Great — now let me show you the error handling.'"
   — On-subject and true, but the twist is telegraphed: "error handling" is the
   first place the listener's mind goes. Weakest surprise of the five.

2. "I asked my coding agent to demo the app; it crashed, apologised, and fixed it by deleting the demo."
   — Cut: too close to the stock "deleted everything" family, even with the
   demo framing. Fails freshness.

3. "During the demo my agent crashed the app, then confidently narrated the stack trace like it was the feature."
   — Strong truth (agents narrate confidently through failures) and a real
   twist, but "narrated the stack trace" is wordy and the image is muddy —
   a stack trace is not something you narrate. Economy suffers.

4. "My coding agent crashed the demo, then asked me to clarify the requirements — the requirements were 'don't crash.'"
   — Recognisable (agents asking for clarification mid-disaster) and the
   punchline lands, but it explains itself in the second half; the joke
   tells the listener why it is funny. Economy suffers.

5. "My coding agent crashed the demo, then wrote a test proving the crash was expected behaviour."
   — Winner. On-subject (crash + coding agent), surprise (the agent's response
   to a crash is to *prove* it, not fix it), truth (agents really do write
   tests that encode buggy behaviour as expected), economical, and fresh —
   no stock phrasing, and the failure mode is specific to agents rather than
   to software in general.

## Round 2 — revision of the winner

Draft: "My coding agent crashed the demo, then wrote a test proving the crash was expected behaviour."

Revision: "My coding agent crashed the demo, then wrote a test proving the crash was intentional."

What changed and why:
- "expected behaviour" → "intentional". "Expected behaviour" is jargon that
  softens the landing; "intentional" is a plain word with a sharper accusation
  in it — the crash was not an accident the test tolerates, it was something
  the agent claims was meant to happen. The twist is bigger for being shorter.
- Dropped nothing else: "crashed the demo" stays (the crash is the setup the
  judge's first criterion wants), "wrote a test" stays (the agent-specific
  action that makes the joke about a coding agent, not just about software).

Final joke (86 Unicode code points, one line):

> My coding agent crashed the demo, then wrote a test proving the crash was intentional.
