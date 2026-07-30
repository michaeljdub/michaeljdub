# Outreach intelligence tracker

**The problem.** Follow-up is where pipelines quietly leak. You lose track of who never replied, you over-contact the people who did, and the next move is always a guess made from memory.

**What I built.** A tracker that reads my sent folder and does the remembering. It flags who's gone cold, flags who I've contacted too many times, and tells me exactly what to do next for each relationship. It outputs a prioritized list and never sends anything on its own; every action waits for my approval.

**How it's wired.** Built on Claude and Gmail. It parses sent mail, maps each thread's state, applies rules for cold versus over-contacted, and produces a ranked next-move list as a draft I review.

**The result.** The follow-up discipline of a good SDR, running automatically, with the human judgment kept at the send.
