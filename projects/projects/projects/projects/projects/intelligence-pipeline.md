# Signal-to-brief intelligence pipeline

**The problem.** The most useful competitive signal lives in unstructured public conversation, not in reports. It's there, but reading all of it every week is a full-time job nobody has.

**What I built.** A multi-agent pipeline that turns that raw discussion into a structured weekly brief. Browser automation gathers the public signal, a fast vision-and-triage model sorts and filters it, and a stronger synthesis model writes the brief. It runs on a cadence and lands as a finished read.

**How it's wired.** Playwright drives the collection. Two Claude models split the work by cost and capability: the lighter one handles volume and triage, the heavier one handles synthesis and judgment. The output is a brief a person actually wants to read on a Monday, not a dump of raw data.

**The result.** A standing intelligence habit that runs itself. The week's signal, filtered and synthesized, without the week of reading.

**Note.** Described generically. No named sources or platforms.
