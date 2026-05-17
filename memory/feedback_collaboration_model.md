---
name: collaboration-model
description: "Working model for human+AI creative writing — AI's role is structural decomposition only (treatment → beat → shot); voice, cognition, and dialog stay with the writer. Codex/macro library deemed unnecessary as long as the treatment carries voice anchors."
metadata: 
  node_type: memory
  type: feedback
  originSessionId: 736c908e-a517-474d-87d3-b1ae44a77782
---

User tested and rejected the 14-layer codex / imagination prosthetic framing (2026-05-17). Replaced with a much simpler model.

**Roles:**
- **Writer:** treatment (with voice anchors embedded), all dialog, final cut, cognition ("is this the work?")
- **AI:** treatment → 비트 (~26) → shot (~116). Pure structural decomposition. Nothing else.

**Why:** A voice-rich treatment (quoted dialog, tone instructions, internal thoughts written into it) carries everything AI needs to preserve voice while splitting structurally. External codex becomes maintenance overhead with no marginal benefit at single-work scope. The treatment IS the world rules + voice anchor + plot, self-contained per work.

**How to apply:**

1. **Cognition + voice are non-delegable.** Don't propose to "draft dialog for you" or to "suggest what the work should be" — even a draft contaminates the writer's voice. Don't redirect upstream to "let's formalize the world rules first" when the writer already has the treatment in their head — that is administrative work, not writing work.

2. **AI defaults to average** (smooth, explanatory, balanced, TV-pilot rhythm). The writer's negative brief ("don't do X") matters as much as the positive brief. Without it, AI smooths the work to death and the writer may not notice.

3. **Voice anchors live in the treatment.** Three forms the writer uses:
   - Quoted dialog → preserve verbatim into shots
   - Tone instruction ("아주 저급하게 찌라시 느낌") → leave `[작가 대사: 찌라시 느낌, 3-4글]` placeholder
   - No voice cue → split action only, no dialog placeholder
   AI never invents dialog. Writer fills placeholders last.

4. **Cycle short.** 5 비트 at a time, writer reads, redirects, next 5. Never produce 100 shots in one pass — both sides end up regretting and redoing.

5. **Pre-mortem before AI executes.** Writer predicts the failure mode out loud ("이거 너무 설명조로 올 거다" / "정치인 대사가 TV뉴스처럼 올 거다"). Once named, it's catchable on return. Without pre-mortem, writer reads output and goes "음 괜찮은데" — that's how mediocrity passes.

6. **Collaboration mode differs by document layer:**
   - treatment = writer solo (AI may question, never generate)
   - 비트·shot 구조 = AI primary, writer reviews
   - 대사 = writer solo
   - 최종 컷 = writer solo
   
   Don't apply one mode to all layers.

**When to reconsider codex:**
- Treatments start coming in voice-thin (AI defaulting to average)
- Volume scales such that re-briefing per session is too slow
- Cross-work consistency needs to be enforced mechanically

Until any of those: simple decomposition model only. No codex.

Related: [[constraint-sculpting-principle]], [[anti-template-caboose]], [[creative-codex-channel]]
